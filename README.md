# Starcom Internship Documentation

A central, living knowledge base for interns across multiple tracks (cybersecurity, intelligence, business, marketing, blockchain & technology, legal & ethics, and more). This repository organizes shared concepts, glossaries, playbooks, and onboarding materials to help you ramp quickly and contribute effectively.

## Repository structure

Current folders
- intern-glossary/ — Cross-track glossary terms with examples and bilingual support (Mandarin + Pinyin, Hindi + transliteration).

Planned folders (roadmap)
- onboarding/ — Setup guides, accounts, security basics, workspace tips.
- playbooks/ — Step-by-step procedures for recurring tasks and investigations.
- projects/ — Project briefs, milestones, deliverables, and templates.
- tools/ — Tooling references, quickstart guides, and cheatsheets.
- templates/ — Reusable report, brief, and checklist templates.
- training-paths/ — Role-specific learning paths and competency maps.

Note: If you don’t see a planned folder yet, treat it as a placeholder for future content.

## Getting started

- Browse the intern-glossary to learn shared vocabulary and context.
- Use the examples and emoji cues to understand practical usage and nuance.
- When you add content, follow the style and contribution guidance below.

## Contribution workflow

- Branch and PR
  - Create a feature branch: docs/<short-topic> (e.g., docs/marketing-advanced-terms)
  - Use Conventional Commits for messages: docs: add 10 marketing terms
  - Open a pull request with a concise description and checklist

- File naming
  - Use numbered, kebab-case markdown files for ordered series (e.g., 01-cybersecurity.md)
  - Keep names short, descriptive, and consistent across folders

- Glossary entry format (required)
  - Bullet list with bold English term, concise definition, one short example, and both translations:
    - English line: - **Term** — Short, clear definition.
    - Example line: - Example: Practical, 1-sentence scenario.
    - Mandarin line: - Mandarin: 中文 (Pinyin)
    - Hindi line: - Hindi: देवनागरी (Transliteration)
  - Keep entries skimmable; prefer one sentence per sub-bullet
  - Add relevant emoji for quick visual cues when helpful (don’t overuse)

- Translation requirements
  - Mandarin: Provide Chinese characters and Pinyin with tone marks when possible
  - Hindi: Provide Devanagari script with a simple, readable transliteration
  - Be consistent with existing terminology; prefer standard industry usage

- Quality checklist before PR
  - Terminology is accurate and neutral; definitions are concise
  - Example is realistic, non-sensitive, and adds clarity
  - Both Mandarin + Pinyin and Hindi + transliteration are present
  - Term is bolded at the start of the bullet
  - Emoji used only when it aids scanning or context
  - Spelling/grammar pass complete; headings and lists render properly

## Style guide (docs)

- Write for clarity and actionability; prefer short sentences
- Use present tense and active voice where possible
- Keep definitions vendor-neutral; add examples that generalize
- Avoid sensitive data and proprietary details in examples
- Prefer consistent emoji: 🎯 audience, 💡 value, 📊 analytics, 📜 contract, 🧬 forensics, etc.

## Governance and versioning

- This is a documentation-first repository; changes are reviewed via PRs
- Use Conventional Commits; scope with the folder (e.g., docs(glossary): ...)
- Major structural changes should include a brief rationale in the PR description

## License

See LICENSE in the root of this repository for licensing terms.

## Feedback and support

- Propose improvements via issues or pull requests
- Tag maintainers in PRs for faster reviews
- If a translation is disputed, include sources or rationale in the PR

---

Welcome aboard. Contribute early and often—small, clear updates compound into great docs.
