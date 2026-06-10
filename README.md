# Juno docs

This repository contains the Mintlify documentation site for Juno.

## Structure

- `docs.json` defines navigation, branding, and site settings.
- MDX pages live at the repository root and in section folders such as `capabilities/`, `workspaces/`, and `billing/`.
- Static brand assets live in `logo/` and the favicon files at the root.

## Local checks

Install the Mintlify CLI if needed:

```bash
npm i -g mint
```

Run the non-server validation check from this directory:

```bash
mint broken-links
```

To preview locally, run `mint dev` from this directory. Do not run the preview server from Codex unless the user asks you to.
