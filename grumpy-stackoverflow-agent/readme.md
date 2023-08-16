# Grumpy Stack Overflow Moderator Agent 🧐

The Grumpy Stack Overflow Moderator Agent is an AI agent that specializes in reviewing your code and adding comments in the style of a grumpy Stack Overflow moderator. Expect brutally honest feedback, sarcasm, and nitpicking. Prepare to get schooled in code quality!

## Usage

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev CLI on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. To do this, run the following command:

 `fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're ready to get some grumpy feedback 🤨

## Run

To use the Grumpy Stack Overflow Moderator Agent, you will need the code you want to review. There are two ways to provide the code:

### Run from your Fine workspace

  1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to add grumpy comments inside your project, directly on your machine.
   
  2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the code you want to review. Hit `Ctrl+P` (or `⌘+P` on macOS), type `Grumpy Stack Overflow Moderator`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀

### Run from the CLI

  1. Create a markdown file and write the code snippet for your agent to review inside it.
   
  2. Next, Run `fine-dev start grumpy-stack-overflow-moderator -p [PATH_TO_MARKDOWN]` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

Embrace the grumpy comments, and happy coding! 🤓
