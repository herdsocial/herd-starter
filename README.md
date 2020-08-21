# Herd Slackbot Starter 🔥✨🐑

This simple template uses Typescript, `nodemon`, `yarn`, `@slack/bolt`, `ngrok` (or any other ssh tunneling service) and `express` for serving. It's super easy to deploy (unfortunately, it doesn't come with Github Actions or CI because of `.env` parameters, but feel free to make a general-purpose PR!)

## Installation

Prerequisites that should be installed:
- Node.js (V14+ is recommended)
- Ngrok
- Git (and a Github account)

## Getting started

1. Run `git clone https://github.com/herdsocial/bolt-starter-herd <your-bot-name>` to grab all source code
2. Run `yarn` to install all dependencies
3. Run `yarn start` to spin up an Express server
4. In another shell, run `yarn portal` to begin forwarding the local server on `localhost:5000` to an `ngrok` subdomain.

### Setting up Slack

Follow instructions from (the official Slack tutorial)[https://slack.dev/bolt-js/tutorial/getting-started] to spin up a Slack bot instance.

## Development

All source code is stored in `src/`, and all subfolders are descriptive. Features are loaded using ES6's dynamic imports for automatic codesplitting!