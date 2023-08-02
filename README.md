<div align=center>
    <a href="https://fine.dev">
  <img height="80px" src="https://uploads-ssl.webflow.com/6290be8d112ee934eeb6aaf2/64745d685739d23f87bf7ec1_android-chrome-256x256.png"/>
  </a>
    <br>
  <h1>Fine</h1>
  <p>Automate software development with AI Agents</p>
</div>
<br>
<p align="center">
    <a href="https://thisis.fine.dev/">
      <img src="https://img.shields.io/website?url=https://thisis.fine.dev/" 
          alt="Website"></a>
    <a href="https://docs.fine.dev/">
        <img src="https://img.shields.io/badge/Docs-9654EB"
            alt="Docs"></a>
    <a href="https://discord.gg/nxW8sA5yqe">
        <img src="https://img.shields.io/discord/308323056592486420?logo=discord"
            alt="Discord"></a>
    <a href="https://twitter.com/intent/follow?screen_name=thisisfinedev">
        <img src="https://img.shields.io/twitter/follow/thisisfinedev?style=social&logo=twitter"
            alt="follow on Twitter"></a>
</p> 
<p align="center">
<a href="https://www.fine.dev/">
<img src="https://github.com/finehq/agent-examples/assets/119014147/85f4a895-8377-45bf-840d-ed58decd012a">
<br>
</a>
</p>

This repository contains a number of ready-to-run example agents that you can use to automate your software development workflow.
Pick an example and follow the instructions in the corresponding README.

## Get started

### Install Fine CLI
To get started with Fine, you need to install the Fine CLI tool. You can do this by running the following command:

```
npm install -g @fine-dev/cli
```

Next, create your Fine account by running the following command:

```
fine-dev login
```

Follow the instructions to create your account.

### Deploy an agent
To use an agent, you need to deploy it to your workspace. 

Run the following command to deploy the agent and make it available for use in your workspace:

```
fine-dev deploy -p [path to agent configuration file]
```

Once the agent is deployed successfully, you can use it to automate your software development workflow.

### Run an agent

To use an agent, navigate to your project directory and run the following command:


```
fine-dev start [agent-name] -p [path to your project's specifications]
```

You can also use Fine's command palette (Cmd + P inside any notebook) to run the agent.


## Build your own Agent
For more information on how to use Fine and build your own agents, check out the [Fine documentation](https://docs.fine.dev/).


## Why Fine is awesome
Fine lets you build and deploy custom AI Agents that can carry out various coding tasks for you, and automate a great deal of your development workflows. Agents can generate boilerplate code, update your database schema, generate typings, manage APIs, and much more.

### Use cases

Agents can help you with a variety of tasks, including:

- **Automating repetitive tasks**: Certain tasks, like setting up a new project or adding common functionalities, follow the same pattern. Fine Agents can automate these, saving you time and effort.
- **Ensuring code quality and consistency**: Fine Agents can generate code following best practices, ensuring high quality and consistency across your codebase.
- **Running migrations**: Fine Agents can help you modernize your codebase to a new framework or library, or to a new version of an existing framework or library.


## Get in touch

Join our active [Discord community](https://discord.gg/nxW8sA5yqe), where you ask questions, share experiences, and can engage in discussions about Fine or Software 3.0 ideas.

The community is also a good place to share product feedback, report bugs and ask for help when building custom agents and AI workflows.
