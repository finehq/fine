# Typescript Type Generator 🤖

The Typescript Type Generator is an AI agent that specializes in improving type safety and code quality in your Typescript projects. It does this by automatically scanning and updating your .ts files, adding explicit types where they are missing.

## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. To do this, run the following command:

 `fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're ready to roll 🏎️

## Run

To use the Typescript Type Generator, you will need to give it access to your Typescript project:

### Run from the CLI

Run the following command inside the project you would like the agent to make modifications to:

`fine-dev start typescript-type-generator` 

 You can also specify a scope for the agent to work within. This is a path or a glob pattern that will be used to filter the files the agent will work on. For example, if you only want the agent to work on `.ts` files inside the `src/components` directory:

`fine-dev start typescript-type-generator -s src/components/**/*.ts`

## Agent Steps

The Typescript Type Generator agent has the following steps:

1. **Generate plan**: This step generates a work plan for updating types in the .ts files.
2. **Execute plan**: This step executes the plan, either updating the .ts files with inferred types or adding TODO comments where manual review is needed.
