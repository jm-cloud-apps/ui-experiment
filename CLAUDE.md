# CLAUDE.md

This repository is a lightweight static web app for Ultimate Football.

## Quick context
- Main file: index.html
- No build step, no package manager, no tests
- State is stored in browser localStorage

## Agent guidance
- Treat index.html as the primary implementation file.
- Keep edits focused and preserve game behavior.
- Avoid introducing dependencies or splitting the app into many files unless requested.
- If you change save data or game state structure, preserve backward compatibility where possible.

## Run locally
- python3 -m http.server 5199 --directory .
