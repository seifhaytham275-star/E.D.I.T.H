# E.D.I.T.H.

**Enterprise Digital Intelligence & Task Handler** — a responsive Arabic-first workspace for planning tasks, reviewing proposed steps, and preparing integrations for a secure AI agent.

## Current status

This repository currently contains a static front-end prototype. It provides:
- Arabic RTL responsive dashboard for desktop, tablet, and mobile.
- Local task planning with reviewable suggested steps.
- Task list and local activity log.
- JSON report export.
- Integration status cards and safety-oriented settings.
- Clear distinction between planning in the browser and real external execution.

## Important limitations

The current version does **not** call an AI model or execute external actions. GitHub, live web research, browser automation, automated tests, and deployment integrations require a backend and authenticated service connections. The UI does not ask for or store API secrets.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Deploy

The static site can be deployed to a static hosting provider by connecting this repository and using the repository root as the project directory. No build command is required; `index.html` is the entry point.

## Security roadmap

1. Add a server-side API endpoint for the chosen AI provider.
2. Store API keys only as hosting-provider environment variables.
3. Add authenticated, least-privilege GitHub integration.
4. Add explicit approval gates for file writes, commits, browser actions, and deployment.
5. Add server-side logging and automated tests before enabling execution.

## Project

Repository: https://github.com/seifhaytham275-star/E.D.I.T.H
