# Editorial Ownership

An optional presentation style approved through the workshop's two ownership and visibility studies. The approval concerns the visual direction. Its workplace examples are not instructions for other users or organisations.

## Character

Clear, composed, tactile, and precise. Strong editorial typography gives the point weight. Diagrams explain a physical relationship, such as a constraint, route, connection, or changing state. Halftone texture gives an explanatory object a printed feel without sacrificing clear geometry and labels.

## Palette

| Role | Light treatment | Dark treatment |
| --- | --- | --- |
| Ground | `#EEEEE6` | `#181C1B` |
| Main ink | `#202326` | `#EEEEE6` |
| Supporting text | `#64675E` | `#B8BFB0` |
| Explanatory accent | Electric blue `#393CF5` | Soft lime `#BACD89` |

Use the accent to identify the route, state, or key label. Keep color meanings consistent within a story. These treatments can provide deliberate chapter contrast, but changing light to dark does not by itself make a new composition.

## Type and scale

The approved HTML studies used Outfit for the main text, JetBrains Mono for small annotations, and Georgia italic for a small amount of expressive emphasis. Use installed or appropriately licensed equivalents when necessary and check their metrics in the target format. The CSS does not fetch fonts or supply font files.

At a 1440 × 810 presentation canvas, useful starting values are:

- Outer inset: 66 px horizontally, approximately 53 px vertically.
- Main headline: 82–90 px, regular weight, compact leading, restrained negative tracking.
- Explanatory body: 23 px with comfortable line spacing.
- Supporting qualification: 16–18 px.
- Small annotations: 12–14 px, monospace, lightly tracked.

These are prototype values, not minimum readable sizes for every room. Enlarge annotations when projected or viewed at a distance. Preserve the hierarchy rather than mechanically copying pixel values into PowerPoint.

## Composition vocabulary

Use the composition that explains the idea:

- An editorial split for a strong proposition and one substantial explanatory diagram.
- A full-width field for a process, comparison, or transformation that needs spatial continuity.
- A typographic ledger for concise states that genuinely need to be read together.
- A large central diagram with short surrounding annotations for dependencies or relationships.

Keep alignment, typographic hierarchy, margins, and source treatment recognisable across these forms. Do not make a full presentation out of duplicate splits or ledgers. Use one strong visual idea per frame unless a comparison requires more.

## Diagram material

Combine crisp SVG or native vector lines with an original halftone object when a physical metaphor helps. Form the object from dots with varying size or density to suggest volume. Keep it separate from the lighter background grid. A connector should remain crisp and easy to follow through the texture.

Use labels at the point they explain, with enough clearance from curves and object edges. Add fine construction lines or brackets only where they clarify continuity, grouping, or scope. Omit decorative grids when they reduce legibility.

If marks represent data, use an accurate scale and legend. Texture alone must not imply measured counts. Do not reuse the obstacle metaphor for ideas it does not explain.

## Motion signature

Make the explanation change state. Preserve a carrier, such as the same task marker, across a route or transformation so the viewer can follow what remains constant. Reveal a label as its corresponding step becomes relevant. Use smooth acceleration and deceleration, then hold the complete explanation.

The prototype's route takes approximately 6.4 seconds and its four-state reveal approximately 4.2 seconds. Adjust these to the amount of reading and the speaker's pace. Provide replay, pause, and a complete-state control for browser presentations. Respect reduced-motion preferences. Do not add perpetual breathing or wobble to fill a hold.

The static state must still communicate the point. Browser motion is not automatically portable to a slide application; use native equivalents or agree on a different delivery format.

## Reusable implementation

[tokens.css](tokens.css) supplies scoped colors, type stacks, spacing, and easing for HTML prototypes. Add `data-style="editorial-ownership"` to the presentation root and optionally `data-tone="dark"` to a section. For other presentation formats, translate these design values into that format's theme and native objects.

Keep the user's source claims, tone, and desired outcome authoritative. Reuse the visual language, not the example's wording or workplace expectations.
