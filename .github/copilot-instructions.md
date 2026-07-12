# Copilot instructions for ui-experiment

This repository is a self-contained browser game. The main implementation is in index.html.

## Priority rules
- Keep the app as a single-file static experience unless the user explicitly asks for changes that require a build system.
- Preserve existing localStorage save behavior and the uf-save-v3 state shape.
- Avoid unnecessary refactors or dependency additions.
- Make small, targeted changes that preserve gameplay and UX.

## Where to edit
- index.html for gameplay, UI, styles, and state logic
- README.md for user-facing docs
- .claude/launch.json for local run/debug settings

## Verification
- Confirm the game still loads locally after changes.
- Ensure basic interactions like opening packs and switching tabs still work.
