# Contributing to EinzzTools Frontend (`einzzcookie.org`)

Thanks for helping improve the EinzzTools web interface. Please keep pull requests focused, lightweight, and easy to review.

## Getting Started
* **Fork & Clone:** Fork the repository, clone it locally.

## Code & UI Guidelines
* **Keep Dependencies Minimal:** Prefer vanilla HTML, CSS, and JavaScript over heavy frameworks or external libraries to keep page loads fast.
* **Respect Existing Themes:** Ensure all new UI elements, modals, and status badges work cleanly across every built-in theme (`Light`, `Dark`, `Dossier`, `Night watch`, `Redacted`, `Sepia print`, and seasonal themes).
* **Handle API States Gracefully:** Always include clear loading, empty, rate-limit, and error states (e.g., missing user, private data, or endpoint downtime) without breaking the page layout.
* **No Hardcoded Secrets:** Never commit API keys, `x-email` / `x-api-key` headers, tokens, or personal test accounts into frontend source files or logs.

## Submitting Changes
* **Test Before Pushing:** Verify that all features and layouts are still functioning before you push.
* **Clear Pull Requests:** Summarize what changed, why it was needed, and attach before/after screenshots for any visual or layout updates.
* **Bug Reports:** Include the browser version, active theme, endpoint/tool affected, and steps to reproduce the issue.
