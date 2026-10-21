# General work Skills

Three public starter adaptations for carrying work forward, reviewing it together and improving the process. Use them with an agent or workflow tool that supports reusable skill instructions. Adapt them to your work; they do not include project records or account access.

## Manage Work

Keep a substantial task moving across milestones. Reconcile the goal and existing backlog, choose the next useful outcome, verify the result and continue within the authorized scope.

[Open the skill folder and install Manage Work](https://github.com/kobex-oai/starter-skills/tree/main/skills/manage-work)

Try this prompt:

> Use $manage-work to review this project's goal and backlog, choose the next useful milestone, and carry the authorized work through verification

## Thread Workflow

Work through artifacts and decisions in one vertical checklist. Keep reviewed progress separate from whether the underlying work is done. Use supported interactive controls when available, otherwise use Markdown.

[Open the skill folder and install Thread Workflow](https://github.com/kobex-oai/starter-skills/tree/main/skills/thread-workflow)

Try this prompt:

> Use $thread-workflow to help me review these files one at a time, with source links, clear checks and recorded decisions

## Reflect and Refine

Review selected work for recurring paper cuts, distinguish avoidable rework from normal iteration, and choose the smallest durable improvement. A review-only request returns proposals.

[Open the skill folder and install Reflect and Refine](https://github.com/kobex-oai/starter-skills/tree/main/skills/reflect-and-refine)

Try this prompt:

> Use $reflect-and-refine to review these three completed tasks, identify recurring friction, and propose the smallest fixes before editing anything

## Install or try one skill

Use your current agent's supported skill installer with the linked repository and the chosen `skills/<name>` folder. Ask it to inspect all files, verify the current installation location, preserve an existing version and show differences before replacement. It should verify the installed result and tell you how to invoke it.

If there is no installer, download and extract the repository ZIP. Give your agent the selected skill folder and ask it to read `SKILL.md` and apply those instructions to one task without installation. Keep Reflect and Refine's `references/` folder together with its entrypoint.

These are instruction-only starter skills. They require no connector, external package, executable template, host-specific API or background process. Available workers, interactive surfaces and access to work material depend on your current tool and permissions. Nothing here grants broader access or authorizes publication, sending, deployment or a recurring schedule.

The exact files and hashes are in [skills-manifest.json](skills-manifest.json). Installation and available features should be verified in the receiving tool.

## Attribution

Manage Work was inspired by [Matt Shumer's Manager Loop](https://x.com/mattshumer_/status/2095723177389232540) and developed into a general workflow for bounded assignments, evidence-based acceptance, replanning and recovery. This starter adaptation does not copy the post or imply its author's endorsement.
