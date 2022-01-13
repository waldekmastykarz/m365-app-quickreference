# Node.js Teams bot connected to M365 using Single Sign-On

## Prerequisites

Here are the different prerequisites that you'll need to install or configure before you start building this app.

- [Microsoft 365 developer tenant](https://developer.microsoft.com/microsoft-365/dev-program). Available for free for development purposes<br>
  _This is your playground to test the bot before deploying to production_
- [Azure subscription](https://azure.microsoft.com/free). Free trial<br>
  _This is where you register your bot with the Microsoft cloud platform and can deploy resources to host it_
- [Node.js v16.x LTS](https://nodejs.org/)<br>
  _Node.js is the runtime for developer tooling and your bot_
- [Yeoman v4.x](https://www.npmjs.com/package/yo)<br>
  _Yeoman is the engine used to scaffold your bot project_
- [Gulp CLI v2.x](https://www.npmjs.com/package/gulp-cli)<br>
  _Gulp is the task runner that allows you to build, package and deploy your bot project_
- [Ngrok](https://ngrok.com/)<br>
  _During development, you’ll be running your bot on localhost, but will need to register it with the Microsoft cloud using a publicly available Internet URL. Ngrok is a tunnel that allows you to expose your local dev server on an Internet URL._

## Tooling

Here's the tooling that you'll need to install to build this app.

- [Teams Yeoman generator v3.x](https://www.npmjs.com/package/generator-teams)<br>
  _This tool allows you to create a project with a Teams bot matching your specifications._

## App type

- Teams bot<br>
  _This is the type of app you’ll build. Use this string to search for more information about your app._

## App SDK

Your app will use the following SDKs to communicate with apps and services in Microsoft 365 where the app will be exposed.

- [Teams SDK v1.11](https://www.npmjs.com/package/@microsoft/teams-js) (included in the project scaffolded using Teams Yeoman generator)<br>
  _This SDK allows your bot to communicate with Microsoft Teams_
- [Bot Framework v4](https://www.npmjs.com/package/botbuilder) (included in the project scaffolded using Teams Yeoman generator)<br>
  _This SDK allows your bot to receive and respond to chat messages, show dialogs, etc._

## UI

Here are the libraries you'll need to build the UI for your app so that it seamlessly integrates with Microsoft 365.

- Not applicable<br>
  _Teams bots don’t have a UI and are exposed as chat messages inside Microsoft Teams_

## API SDK

You'll need these SDKs to communicate with APIs used by your app.

- [Microsoft Graph JS SDK v3](https://www.npmjs.com/package/@microsoft/microsoft-graph-client)<br>
  _JavaScript SDK to call Microsoft Graph which is the API to access data stored in Microsoft 365._
- [Microsoft Graph TypeScript Types v3](https://www.npmjs.com/package/@microsoft/microsoft-graph-types)<br>
  _TypeScript types for working with Microsoft Graph that give you design-time type safety in your project._

## Identity SDK

Here are the SDKs that you'll need to implement authentication in your app and be able to connect to Microsoft 365.

- Not applicable<br>
  _Authentication is handled by Bot Framework for you and you don’t need a separate SDK to get access tokens_

## API

You'll use the following APIs in your app.

- [Microsoft Graph](https://docs.microsoft.com/graph/overview)<br>
  _The API to access data stored in Microsoft 365_

## Resources

### Learn

Resources on Microsoft Learn that teach you in a structured way how to build this type of app.

- [Microsoft Teams – Authentication and Single Sign-on](https://docs.microsoft.com/learn/modules/msteams-sso/) (units 1, 2, 3, 6, 7, 8)<br>
  _Learn module that explains you the most important concepts related to building Teams bots connected to Microsoft 365 using Microsoft Graph._

### Tutorials

Tutorials that you can follow to learn how to build this type of app step by step.

### Videos

Here are the videos that demonstrate some of the concepts used in this app.

- [Demo - Single sign-on (SSO) with Microsoft Teams bots](https://www.youtube.com/watch?v=jt0QtVzxPXs)<br> 
  _Short video showing step-by-step how to create and configure a Microsoft Teams bot with Single Sign-On. Based on the learn module from the previous section._

### Docs

Official documentation from Microsoft relevant to this type of app.

- [Microsoft Teams bots](https://docs.microsoft.com/microsoftteams/platform/bots/what-are-bots)<br>
  _Documentation that explains what Microsoft Teams bots are and what they can do_
- [Bot Framework](https://dev.botframework.com/)<br>
  _You build Teams bots using the Bot Framework. This documentation explains what bot framework is and how you can use it to build bots on Microsoft technology._

### Feedback

Here's where you can submit feedback, and suggestions for new features.

- [Microsoft Teams](https://feedbackportal.microsoft.com/feedback/forum/ad198462-1c1c-ec11-b6e7-0022481f8472)
  _Go here to share feedback and feature ideas for Microsoft Teams with Microsoft_
- [Microsoft Graph](https://docs.microsoft.com/answers/products/graph)
  _Go here to share feedback and feature ideas for Microsoft Graph with Microsoft_
- Bot Framework
