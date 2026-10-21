---
name: bootstrap
description: 'Use when a user wants to establish setup and conventions for a new or existing project.'
---

# Project Bootstrap Interview

Interview the user to establish setup and conventions for a new or existing project, then record the confirmed decisions in root-level `AGENTS.md`.

## 1. Establish context

Inspect the repository to understand its purpose and current state. Carry forward answers already provided, distinguish existing decisions from open questions, and use that context to guide the interview.

## 2. Interview adaptively

Use the question tool to ask one focused question, then wait. Offer well-maintained, widely adopted options, favoring permissive licenses. Briefly justify recommendations using the user's goals or repository evidence.

Track settled and open decisions and their dependencies. Choose each next question from unresolved choices whose prerequisites are settled; revisit dependent choices when an answer changes. Look up facts rather than asking the user to repeat them.

Every topic below MUST end with an agreed decision, confirmed non-applicability, or explicit user deferral:

- Project purpose.
- Language, frameworks and tooling.
- Unit testing.
- Database access, driver, and migrations.
- Project layout.
- Development commands and which command verify changes.

Explore other setup topics as needed. Finish when each topic is settled, not applicable, or explicitly deferred by the user.

## 3. Confirm the brief

Draft the brief using [assets/AGENTS.md](assets/AGENTS.md) as the output structure for new files. MUST populate only the template's placeholders, using confirmed answers that match each placeholder's scope; add nothing else.

When updating an existing `AGENTS.md`, retain its organization where practical, preserve unrelated existing instructions, and resolve conflicts with the user before requesting confirmation.

Present the complete draft and use the question tool to request confirmation. Revise and seek confirmation again if changes are requested. Write only after confirmation.

## 4. Write the project instructions

Save the confirmed draft to root-level `AGENTS.md`.

Verify that the saved file matches the confirmed draft and each populated section stays within its template placeholder's scope. Check that references to existing files resolve and that planned paths are clearly marked as planned.

## 5. Report next steps

Link to the saved file and summarize any deferred decisions. If follow-up work remains, recommend next steps. Otherwise, report that the confirmed setup is already in place.