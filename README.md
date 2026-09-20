# AI Advantage Skills

Reusable skills for the AI Advantage Workshop: learn from how you already work with AI, and communicate ideas clearly to the people who need to act on them.

## The skills

| Skill | What it does |
| --- | --- |
| [Discover my skills](skills/discover-my-skills/SKILL.md) | Reads accessible chat sessions, finds recurring workflows and feedback, lets you choose a grouping, and creates your reusable skills with source references. |
| [Stakeholder storytelling](skills/stakeholder-storytelling/SKILL.md) | Clarifies the stakeholder and intended outcome, asks for your visual references, and develops presentations or dashboards through explanatory visuals and one or two prototype frames. |

These are early drafts. Skill structure has been validated; end-to-end use in an attendee's ChatGPT account has not yet been verified. The stakeholder skill's first visual prototype is still being developed.

## Install from GitHub

For local agents supported by the [Skills CLI](https://github.com/vercel-labs/skills):

```sh
npx skills add nopefallacy/ai-advantage-skills
```

List the available skills before installing:

```sh
npx skills add nopefallacy/ai-advantage-skills --list
```

Or download the source with Git:

```sh
git clone https://github.com/nopefallacy/ai-advantage-skills.git
```

Cloning downloads the files; it does not activate them in an AI app. Use your app's supported skill installation process and keep each skill's `references` folder with its `SKILL.md`.

The `npx skills` command uses the existing Skills CLI to fetch this GitHub repository. This library does not need its own npm publication for that command to work.

## Using ChatGPT

ChatGPT is the first intended experience. These local-agent installation commands do not install anything into an ordinary ChatGPT web conversation.

Current [OpenAI guidance](https://learn.chatgpt.com/docs/build-skills) describes selecting skills with `@`, standalone skills in the desktop app, and plugin-bundled skills across web, desktop, and mobile. Use the path actually supported by your account. A ChatGPT plugin listing for this library has not been published.

As a manual starting point, supply the selected `SKILL.md` and its supporting references to a conversation and ask ChatGPT to follow it. This supplies instructions for that conversation; it is not a persistent installation and does not add access to other sessions. This manual path still needs attendee testing.

For discovery, actual accessible conversations are the evidence. If ChatGPT cannot retrieve enough history, the skill explains what it can see and offers either to proceed with that material or to accept more conversations or a description of a recurring task. It does not promise a full account-history scan.

## npm package

The source includes a package manifest for `ai-advantage-skills`. Publication to the npm registry is pending authentication. Until a release is verified, use the GitHub route above.

The npm package contains skill instructions and references, with no install hooks or bundled runtime. Installing that package downloads the skill files; activation still depends on your AI app.

## Visual direction

Stakeholder storytelling asks for your screenshots, sample deck, brand guidance, written style description, or another available skill. Its editorial dots, halftone, pixels, and geometric treatments are optional directions. The content and stakeholder determine the visual explanation; the style makes that explanation clear and coherent.

## Source material and scope

The library contains reusable instructions. Attendees' conversations and generated personal skills stay in their own output. Reference images used during design review are not bundled here.

Additional workshop skills will be developed separately. This release contains only the two skills listed above.
