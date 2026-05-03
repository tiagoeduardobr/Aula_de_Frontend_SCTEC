# AGENTS.md

## Project Preferences

- Always write commit messages in English.
- Use semantic / conventional commit messages when possible.
- Always push committed changes to the tracked remote when the user asks to version or commit work.
- Keep changes minimal and focused on the requested task.
- Preserve the existing Portuguese content style in the project files unless the user asks otherwise.
- Treat this repository as a frontend exercise for the SCTEC quick track of Software Development.
- When updating the README, keep the SCTEC / SENAI context visible and concise.
- Prefer simple, readable HTML and documentation over overengineered solutions.

## Documentation & Linting Rules

When creating or updating documentation files (`.md`, `.json`, `.html`), follow these rules:

- **MD047/single-trailing-newline:** All files must end with a single newline character (no blank lines at EOF).
- **MD012/no-multiple-blanks:** Use maximum 1 consecutive blank line between sections (not 2 or more).
- **Spellcheck:** Add custom words to `cspell.json` under the `words` array (e.g., project names, proper nouns, technical terms) instead of ignoring them globally.
- **HTML:** Ensure all tags are properly closed (`<ul>`, `<p>`, `<section>`, etc.) to avoid linting errors.
