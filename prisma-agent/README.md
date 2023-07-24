# Prisma Agent
The Prisma agent is an AI agent that automates the process of generating and updating your Prisma schema file based on your project's specifications.

## How to Use 
To use the Prisma agent, you need to have Fine platform installed. Once you have installed Fine Agents, you can run the agent using the following command:

### Deploy

To deploy the agent and make it available for use in your workspace:

`fine deploy -p prisma-agent.yaml`

### Run
To use the agent, either use the Fine's Command Palette or run the following command:

`fine start prism-agent -s [path to your project's specifications]`

This command will start the agent and allow you to use it to generate and update your Prisma schema file.

## Agent Steps
The Prisma agent has the following steps:

1. Clarify specifications: This step clarifies the specifications for the data model update.
2. Update Data Model: This step generates and updates the Prisma schema file based on the specifications.
3. Validate & Format: This step validates and formats the Prisma schema file.