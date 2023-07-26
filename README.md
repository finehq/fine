<p align=center>
    <a href="https://www.fine.dev/">
  <img height="80px" src="https://uploads-ssl.webflow.com/6290be8d112ee934eeb6aaf2/64745d685739d23f87bf7ec1_android-chrome-256x256.png"/>
  </a>
  <br>
  Automate software development with AI agents
</p>
<br>

------

<p align="center">
  <a href="https://www.fine.dev/">Fine</a> | <a href="https://docs.fine.dev/">Docs</a>
</p>

<br>

This repository contains a number of ready-to-run example agents that you can use to automate your software development workflow.
Pick an example and follow the instructions in the corresponding README.

## What is Fine?
Fine lets you build and deploy custom AI agents that carry out various coding tasks and automate a great deal of your development workflows. Agents can generate boilerplate code, update your database schema, generate typings, manage APIs, and much more.

### Use cases

Agents can help you with a variety of tasks, including:

- **Automating repetitive tasks:** Certain tasks, like setting up a new project or adding common functionalities, follow a defined pattern. Fine's agents can automate these tasks, saving you time and effort.
- **Ensuring code quality and consistency:** Fine's agents can generate code that follows best practices, ensuring high quality and consistency across your codebase.
- **Running migrations:** Fine's agents can help you modernize your codebase by switching to a new framework or library, or to a newer version of an existing framework or library.


## Get started

### Install the CLI tool
To get started with Fine, you'll need to install the CLI tool. You can do this by running the following command:

```sh
npm install -g fine-dev
```

Next, create your Fine account by running the following command:

```sh
fine login
```

Follow the instructions to create your account.

### Deploy an agent
To use an agent, you need to deploy it to your workspace. 

Run the following command to deploy the agent and make it available for use in your workspace:

```sh
fine deploy -p [path to agent configuration file]
```

Once the agent is deployed successfully, you can use it to automate your software development workflow.

### Run an agent

To use an agent, navigate to your project directory and run the following command:

```sh
fine start [agent-name] -s [path to your project's specifications]
```

You can also use Fine's command palette to run the agent.


## Build your own Agent
For more information on how to use Fine and how to build your own agent, check out the [documentation](https://docs.fine.dev/).


## Get in touch

Join our active [Discord community](https://discord.gg/nxW8sA5yqe), where you can ask questions, share experiences, and engage in discussions about Fine or Software 3.0.

The community is also a good place to share product feedback, report bugs and ask for help when building custom agents and AI workflows.
