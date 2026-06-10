# Documentation project instructions

## About this project

- This is the Juno documentation site built on Mintlify.
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json`.
- Run `mint broken-links` to check links.
- Do not run `mint dev` unless the user explicitly asks you to start a preview server.

## Terminology

- Use "Juno" for the product.
- Use "workspace" for a shared team context.
- Use "task" for delegated work.
- Use "connector" for a connected tool integration in user-facing docs.
- Use "credits" for metered usage.

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise.
- Use sentence case for headings.
- Use bold for UI elements: Click **Settings**.
- Use code formatting for file names, commands, paths, and code references.
- Prefer concrete examples over abstract claims.

## Content boundaries

- Document user-facing behavior, not internal admin tools.
- Do not hardcode unstable pricing or credit-cost numbers unless they are sourced from product copy or code.
- Keep connector descriptions aligned with the app's available connector catalog.
