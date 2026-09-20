# Build and install the agreed process

Read this after the conversation has resolved the material requirements.

## Package the knowledge

Use the target app's supported skill format. For environments using `SKILL.md`, create a folder named with a short lowercase, hyphenated action name. Include YAML frontmatter with `name` and `description`; the description should explain what the skill does and when to use it.

Write instructions for a future AI that has not seen this conversation. Include the agreed outcome, variable inputs, reusable context, decision rules, quality criteria, and relevant limits. Make explicit which missing inputs require questions at runtime. Do not hardcode a sample client's details or example numbers as universal defaults.

Keep substantial conditional guidance in linked references and explain when to read them. Include an output template only when a stable structure matters. Add scripts only when executable work is needed and can be tested. Keep credentials out of skill files; use the app's supported credential handling if the actual workflow needs it.

A single coherent workflow usually needs one skill. If separate skills become necessary because purposes or processes genuinely differ, explain that briefly and resolve the structure with the person. Shared preferences can stay in a reference. Do not split each procedural step into a skill.

## Check that it can work

Use the available format validator. Resolve every local reference and remove unfinished placeholders. For new executable helpers, test their meaningful behavior in an isolated location.

Walk through an actual supplied example when available, or label a constructed example as illustrative. Check that required inputs exist, decisions follow the person's rules, and the output meets the agreed criteria. Do not perform external business actions as part of this check unless independently authorized. If only a walkthrough was possible, report it as such instead of claiming a successful live run.

## Install in the current environment

Inspect the app's actual skill-management capability or documented local skill directory. Use available native tools or current official installation instructions. A skill cannot grant itself filesystem access or add an installation feature to a chat app.

When a writable, supported local destination is established, install the complete folder, preserving references and assets. Check for a name collision before writing. Update an existing skill if that is the requested task; otherwise use a distinct descriptive name or ask when the choice affects which skill the person invokes. Do not replace an unrelated installation.

Verify that installed files match the validated source. If the app exposes a skill list or registry, check recognition there. If it requires a restart or new session, state that activation is pending that step. File placement alone does not prove successful invocation.

When direct installation is not available, provide a portable folder or archive and the app-specific next step you can verify. If the app can only accept attached or pasted instructions, clearly label that as use within the conversation, not persistent installation. Do not invent a slash command, menu, or command-line installer.

Publishing the workshop's builder skill does not authorize publishing the personal skills it creates. Keep the person's process, examples, and generated files in their chosen destination unless they separately request sharing.
