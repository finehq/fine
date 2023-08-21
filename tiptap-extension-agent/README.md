# Tiptap Extension Agent 🤖

If you ever tried creating a plugin for [Prosemirror](https://prosemirror.net/), you know it's no easy task. [Tiptap](https://tiptap.dev/) has given us a wrapper for plugins in the form of extensions, which definitely makes our lives easier, but writing your own extension can still be quite a daunting task...

_...enter the Tiptap Extension Expert! 🎉_

The Tiptap Extension Expert is an AI agent designed specifically for automating the process of generating and updating Tiptap extensions in your project. Extensions are generated based on your project's specifications, using resources that _you_ provide for the task. It might not be the magic pill you were looking for 💊, but this lovely agent will bring you a couple of steps further in your quest for the perfect editor.

## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. To do this, run the following command:

`fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're read to roll 🏎️

## Run

To use the Tiptap Extension Expert, you will need a specification for it to use. There are two ways to provide a specification:

#### Run from your Fine workspace

1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the specification you will be using. Hit `Ctrl+P` (or `⌘+P` on ios), type `Tiptap`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀

#### Run from the CLI

1. Create a markdown file and write the specification for your Tiptap extension project inside it.

2. Next, Run `fine-dev start tiptap-extension-agent -s [PATH_TO_MARKDOWN]` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

## Agent Steps

The Tiptap Extension Expert will go through the following steps while running:

1. **Create update plan:** This step will generate a plan for updating files in your project, based on the provided specification.
2. **Write code:** This step will generate code based on the plan created in the previous step, modifiying files on your machine accordingly.
