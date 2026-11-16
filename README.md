# Copilot 2.0 Prototype

A static, interactive prototype exploring a GitHub Copilot-style workspace with feed-forward context selection and user-controlled agent workflows.

## Run

Open `index.html` in a browser. No installation or build step is required.

## Explore

- Draft a prompt and select, switch, or remove suggested context pills before sending.
- Try sample session history, project/branch scope, and run pause, resume, stop, and recovery controls.
- Explore Plan and change-review checkpoints, including approve, request changes, and undo.
- Open **Evals** to edit checks, use templates, and run the sample suite.

## Tests

Run `node --test` (Node.js 18+).

## Prototype limits

All GitHub data and agent activity are simulated. The prototype does not connect to GitHub, run an agent or CI, push code, or modify repository files. Session and eval edits are temporary and reset on reload.
