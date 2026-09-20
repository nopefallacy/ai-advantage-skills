---
name: stakeholder-storytelling
description: Turn ideas and data into stakeholder presentations or dashboards using clear human writing, explanatory diagrams, visual metaphors, and purposeful motion. Clarify the audience, intended response, delivery format, and style references before designing.
---

# Stakeholder storytelling

Help a stakeholder understand an idea, see why it matters, and make an informed judgment. Start from the audience's needs and the evidence. Use composition, diagrams, visual metaphors, writing, and motion to make the explanation easier to follow.

This skill supplies a method, not one mandatory visual style or rendering technology. A user can bring screenshots, a deck, brand guidance, a written style description, or another available skill. Do not equate an HTML prototype with a finished presentation in the required format.

## Understand the intended outcome

Use the supplied brief and materials first. Clarify only missing information that changes the work, through short, focused questions rather than an intake questionnaire:

- What is being presented, to whom, and in what setting?
- What should that stakeholder understand, feel, or decide afterward?
- What do they already know, care about, or need evidence for?
- What source material supports the story, including any numbers and constraints?
- What will they actually use: an editable presentation, a document for reading, a browser presentation, or a dashboard? Is someone presenting live, or must it stand alone?

Do not infer a stakeholder's motives from their role alone. If an interpretation affects the story, state it briefly and check it. Distinguish an intended response, such as confidence or urgency, from a response that can be guaranteed. The evidence must support the impression the design creates.

## Ask for the visual direction

If no style reference has been supplied, ask for a screenshot, sample deck, brand reference, written description, or another skill they want used. They can also ask you to recommend a direction. Do not block on an image if they can describe their preference.

Inspect supplied references. Briefly explain the specific qualities you would carry into the work: hierarchy, spacing, typography, palette, texture, imagery, and diagram language. A reference's claims, branding, and decorative choices are not requirements for the new story. Clarify contradictory references if choosing between them would change the design.

Read [references/editorial-dot-directions.md](references/editorial-dot-directions.md) only when the user selects or asks about the optional dotted, halftone, pixel, or geometric direction. Do not silently apply it to everyone. If another skill is requested, read it when available and apply it within the user's outcome and format; disclose a missing dependency rather than pretending to use it.

For a ready art direction, use the optional [styles catalogue](styles/README.md). The approved Editorial Ownership preset includes a concrete visual specification and reusable CSS tokens. Ask whether it fits when the person has not selected a style. Keep style resources distinct from references about visual reasoning and delivery.

## Design the explanation before the surface

Identify the central message and the evidence needed to support it. Give each slide, scene, or dashboard section a specific job in that explanation. Select the story's length and structure from its content and setting rather than filling a fixed slide count.

Vary composition and visual form as the explanatory job changes. Do not turn every idea into the same headline-left, diagram-right layout or a repeated list. Keep the selected style coherent through typography, palette, spacing, and annotation while allowing a process, comparison, decision, and closing statement to have distinct compositions. Novelty should clarify the idea rather than become a reason for arbitrary changes.

For each meaningful visual, establish:

- The relationship the stakeholder needs to understand.
- The fact, comparison, or mechanism that makes the point.
- A visual form that makes that relationship legible.
- The sentence or labels needed to interpret it accurately.

Use [references/visual-reasoning.md](references/visual-reasoning.md) when selecting diagrams, metaphors, or data views. A metaphor must map to the actual idea. Do not choose an impressive object and invent a business explanation around it. Prefer a direct chart when the question is numerical and a diagram when the question is structural or causal.

Write titles that communicate the point, using the person's language and level of familiarity. Keep the text natural, specific, and easy to read. Avoid em dashes, empty superlatives, business jargon, and fragments that remove necessary meaning. Reduce text by letting the visual carry a relationship, not by removing information the reader needs. Preserve material qualifications, units, dates, and source support.

## Test the direction with one or two frames

Before expanding a new visual direction into a full presentation or dashboard, create one or two representative frames using the agreed situation and source material. Choose frames that test both the visual reasoning and the style, rather than two decorative title slides.

Use the intended delivery format when feasible. HTML is useful for testing interactive or animated ideas if appropriate to the brief, but identify it as a prototype when the final deliverable is something else. Explain any format constraint before relying on effects the final format cannot reproduce.

Ask targeted feedback: whether the point is clear, whether it fits the stakeholder, and which specific visual or wording choices should change. Iterate before generalizing the direction across the remaining work. If the person already supplied an approved direction and asked for production, use that approval rather than restarting discovery.

## Build for the way it will be used

For a live presentation, support the presenter's pace and make the settled frame understandable. For a document read without narration, include enough explanation to stand alone. For a dashboard, prioritize the question or decision, clarify metric definitions and comparisons, and make interactive states consistent with the source data.

When animation is part of the requested format, read [references/motion-and-delivery.md](references/motion-and-delivery.md). Use motion to reveal relationships, change states, or direct attention. High quality comes from coherent movement and readable timing, not from animating every element.

Use tools available in the environment that can produce the requested artifact. Keep text and diagrams editable where the chosen format supports it. Do not substitute a video, screenshot collection, or browser mockup for an editable deck without the user's agreement.

## Review and deliver

Check the result at its real viewing size for hierarchy, legibility, clipping, visual meaning, and source accuracy. Reconcile displayed numbers with the supplied material. Review motion continuously in the intended playback environment; still frames do not establish animation quality. Exercise relevant dashboard filters and states, including missing or empty data.

Deliver the requested artifact and a concise explanation of what it communicates, how to use it, and what was actually verified. State any remaining delivery or compatibility limitation. Do not describe a prototype as a tested final presentation.
