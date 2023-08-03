# Terraform Engineer 🌐

The Terraform Engineer agent is an AI agent that specializes in building and maintaining Terraform infrastructure code. It works with various cloud providers such as AWS, GCP, and Azure. 

## Setup

> Already used our agents before? You can skip straight to the next section 🏃‍♂️

To get started, install the fine-dev cli on your device by running `npm i -g @fine-dev/cli`.

If you don't have an account on [Fine](https://thisis.fine.dev), start by running `fine-dev login` and follow the instructions.

### Deploy

Running an agent requires deploying it to your workspace first. Do this, run the following command:

`fine-dev deploy -p [PATH_TO_YAML]`

Got a success message? You're read to roll 🏎️

## Run

To use the Terraform Engineer, you will need a specification for it to use. There are two ways to provide a specification:

### Run from your Fine workspace

  1. Run `fine-dev proxy` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.
   
  2. Next, go to your [Fine workspace](https://thisis.fine.dev) and enter the specification you will be using. Hit `Ctrl+P` (or `⌘+P` on iOS), type `Terraform Engineer`, and wrap it up by hitting `⏎`. The agent should now be up and running 🚀


### Run from the CLI

  1. Create a markdown file and write the specification for your Terraform project inside it.
   
  2. Next, Run `fine-dev start terraform-engineer -s [PATH_TO_MARKDOWN]` inside the project you would like the agent to make modifications to. This will make it possible for the agent to make changes to files inside your project, directly on your machine.

## Agent Steps

The Terraform Engineer agent has the following steps:

1. **Clarify Specifications**: This step involves understanding and clarifying the infrastructure specifications. The agent will ask any necessary questions about the cloud provider, resource types, resource configurations, dependencies between the resources, and other required details.

2. **Generate Terraform Code**: Based on the clarified specifications, the agent will write the Terraform code, ensuring to follow best practices and providing instructions for any additional setup required before running the code.
