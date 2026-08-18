# Playbook

Living standards and guidelines, kept in one place and reused across projects. Each doc is meant to be refined over time and referenced from wherever it's needed.

## Contents

### Writing
- **[Avoiding AI Writing Tells](writing/ai-writing-style-guide.md)** — an evidence-based style guide for making copy read like a person wrote it. Covers the tells to cut (lexical, structural, and formatting) and the affirmative-voice work of rebuilding a sentence rather than just trimming it. Includes an editing checklist, a 60-second edit pass, and a drop-in prompt block for steering language models. Application-agnostic.
- **[Voice Spec Template](writing/voice-spec-template.md)** — a template for specifying one person's or one product's voice, to be filled in once and kept alongside the style guide above.

*(More to come: commit conventions, brand voice, prompt snippets, component patterns…)*

## How to use this across projects

- **Reference, don't fork.** Link the canonical file (or a pinned commit permalink) from a project's `README` or `CLAUDE.md` so there's one source of truth.
- **Copy prompt blocks inline.** Where a project needs a prompt block, paste it into that project's code — prompts should be inline, not fetched at runtime. The version here stays canonical; update downstream copies when it changes meaningfully.
- **Refine via commits / PRs.** Treat changes like code, so the history of *why* the guidance shifted is preserved.

## Conventions

- One folder per domain (`writing/`, and others as they appear).
- Each doc is self-contained and carries its own sources and a "last reviewed" date.
- Keep it portable: no project-specific references inside a guide.
