# AGENTS.md

Read this first before making changes to this repository.

## What this repo is
- A small single-page browser game called Ultimate Football.
- The full app lives in one file: index.html.
- UI, game logic, SVG rendering, and browser persistence are all in that file.
- Progress is saved in localStorage under the key uf-save-v3.

## Working style
- Keep changes small and targeted.
- Preserve the single-file/static nature of the app unless the user explicitly asks for a refactor.
- Avoid adding dependencies, build tooling, or new assets unless necessary.
- Prefer editing the existing script/CSS/HTML blocks in index.html over introducing separate files.

## How to run locally
- Start a local server from the repo root:
  - python3 -m http.server 5199 --directory .
- Open http://localhost:5199

## Important constraints
- Do not break save/load compatibility for existing localStorage data.
- Keep the app playable offline and self-contained.
- Preserve the existing game feel and UX.
- Avoid large rewrites of the core game loop.

## Where to look
- index.html: main implementation
- README.md: gameplay overview and deployment link
- .claude/launch.json: local debug/run config

## Before finishing
- Verify the page still loads and the main flows still work.
- Check that localStorage-based progress still saves and restores.
- Keep changes focused on the user request and avoid unrelated refactors.
