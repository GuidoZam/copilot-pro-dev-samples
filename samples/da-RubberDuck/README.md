# Rubber Duck Debugging Assistant 🐤

![Rubber Duck](assets/da-RubberDuck-screenshot.png)

## Summary

Meet your new debugging companion! This declarative agent acts as a "rubber duck" - inspired by the classic programming practice where developers explain their code problems out loud to uncover issues and clarify their thinking. Instead of talking to an actual rubber duck on your desk, you can now interact with an AI-powered debugging assistant that listens patiently and asks thoughtful questions to guide you toward solutions.

![Rubber Duck in use](assets/da-RubberDuck.gif)

### What is Rubber Duck Debugging?

Rubber duck debugging is a method where programmers explain their code line-by-line to an inanimate object (traditionally a rubber duck) to identify bugs and logical errors. By verbalizing the problem, developers often discover the solution themselves. This agent brings that concept to virtual life with intelligent, guided questioning.

### Version history

| Version | Date | Comments |
| --- | --- | --- |
| 1.0 | 16/04/2026 | Initial release |


## Features
- **Patient Listening**: The agent encourages you to explain your problem step-by-step
- **Guided Questions**: Instead of giving direct answers, it asks thoughtful questions that lead you to the solution
- **Problem Breakdown**: Helps break complex issues into smaller, manageable parts
- **Non-judgmental**: Creates a safe space to think through problems without feeling rushed


## Minimal path to awesome

> **Prerequisites**
>
> To run this app you will need:
>
> - [Node.js](https://nodejs.org/), supported versions: 18, 20, 22
> - A [Microsoft 365 account for development](https://docs.microsoft.com/microsoftteams/platform/toolkit/accounts).
> - [VSCode](https://code.visualstudio.com/)
> - [Microsoft 365 Agents Toolkit Visual Studio Code Extension](https://aka.ms/teams-toolkit) version 5.0.0 and higher or [Microsoft 365 Agents Toolkit CLI](https://aka.ms/teamsfx-toolkit-cli)
> - [Microsoft 365 Copilot license](https://learn.microsoft.com/microsoft-365-copilot/extensibility/prerequisites#prerequisites)

1. First, select the Teams Toolkit icon on the left in the VS Code toolbar.
2. In the Account section, sign in with your [Microsoft 365 account](https://docs.microsoft.com/microsoftteams/platform/toolkit/accounts) if you haven't already. Ensure that both "Custom App Upload Enabled" and "Copilot Access Enabled" have green checkmarks
3. Create and provision the Teams app by clicking `Provision` in "Lifecycle" section.
4. Select the "Run and Debug" icon in the left sidebar, and then select `Preview in Copilot (Edge)` or `Preview in Copilot (Chrome)` from the launch configuration dropdown.
5. Once the Copilot app is loaded in the browser, click on the "…" menu and select "Copilot agents". You will see your declarative agent on the right rail. Clicking on it will change the experience to showcase the logo and name of the declarative agent.
6. Ask a question to your declarative agent and it should respond based on the instructions provided.



