# CLI Engineer 🤖

The CLI Engineer agent is an AI agent that specializes in building interactive CLI applications in Typescript using the Commander.js framework.


## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. Do this, run the following command:

 `fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're read to roll 🏎️

## Run

To use the CLI Engineer, you will need a specification for it to use. There are two ways to provide a specification:

### Run from your Fine workspace

  1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.
   
  2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the specification you will be using. Hit `Ctrl+P` (or `⌘+P` on ios), type `CLI Engineer`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀


### Run from the CLI

  1. Create a markdown file and write the specification for your CLI project inside it.
   
  2. Next, Run `fine-dev start cli-engineer -s [PATH_TO_MARKDOWN]` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

## Agent Steps

The CLI Engineer agent has the following steps:

1. **Generate plan**: This step generates a work plan for the CLI application.
2. **Setup Project**: This step sets up a simple boilerplate project for a CLI application in Typescript using commander.js framework.
3. **Generate Commands**: This step generates the relevant CLI commands based on the specifications.