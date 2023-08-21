# React Agent 🤖

The React agent specializes in writing and updating project using React. This agent can implement new components, as well as refactor existing components.

## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. To do this, run the following command:

`fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're ready to roll 🏎️

## Run

To use the React Engineer, you will need to give it access to your FastAPI project:

### Run from your Fine workspace

1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the specification you will be using. Hit `Ctrl+P` (or `⌘+P` on ios), type `React Engineer`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀

### Run from the CLI

Run `fine-dev start react-agent` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

## Agent Steps

The React engineer agent has the following steps:

1. **Generate plan**: This step generates a work plan based on the assignment given.
2. **Execute plan**: This step executes the plan, producing the relevant code for API endpoints, unit tests, or refactors as necessary.
