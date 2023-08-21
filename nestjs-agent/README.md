# NestJS Agent 🤖

The NestJS agent specializes in generating new modules in NestJS applications according to given specifications.


## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. Do this, run the following command:

 `fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're ready to roll 🏎️

## Run

To use the NestJS Module Generator, you will need a specification for it to use. There are two ways to provide a specification:

### Run from your Fine workspace

  1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.
   
  2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the specification you will be using. Hit `Ctrl+P` (or `⌘+P` on macOS), type `NestJS Module Generator`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀


### Run from the CLI

  1. Create a markdown file and write the specification for your NestJS module inside it.
   
  2. Next, Run `fine-dev start nestjs-agent -p [PATH_TO_MARKDOWN]` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

## Agent Steps

The NestJS Module Generator agent has the following steps:

1. **Generate Module**: This step generates a new module for the NestJS application, which may include the following files:
   - .service.ts
   - .controller.ts
   - .module.ts
   - .entity.ts (if needed)
   - .dto.ts (if needed)

2. The agent also updates the existing codebase to use the new module. 

