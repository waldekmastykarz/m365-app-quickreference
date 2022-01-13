# React Single Page App that retrieves data from Microsoft 365

## Prerequisites

Here are the different prerequisites that you'll need to install or configure before you start building this app.

- [Microsoft 365 developer tenant](https://developer.microsoft.com/microsoft-365/dev-program). Available for free for development purposes<br>
  _This is your playground to test the bot before deploying to production_
- [Node.js v16.x LTS](https://nodejs.org/)<br>
  _Node.js is the runtime for developer tooling_

## Tooling

Here's the tooling that you'll need to install to build this app.

- You can create your app project in any way you want. If you don’t use specific tooling, the best way to start is to follow the [React guidance](https://reactjs.org/docs/create-a-new-react-app.html).

## App type

- Single Page App<br>
  _This is the type of app you’ll build. Use this string to search for more information about your app._

## App SDK

Your app will use the following SDKs to communicate with apps and services in Microsoft 365 where the app will be exposed.

- Not applicable<br>
  _Since you’re build a SPA that runs outside of Microsoft 365, you don’t need an app SDK to integrate it in Microsoft 365_

## UI

Here are the libraries you'll need to build the UI for your app so that it seamlessly integrates with Microsoft 365.

- [Microsoft Graph Toolkit (MGT)](https://aka.ms/mgt-docs)<br>
  _Set of login providers and UI components connected to Microsoft Graph, which is the API to access data stored in Microsoft 365. MGT helps you significantly simplify adding authentication and showing data from Microsoft 365 in your app._
- [Fluent UI React](https://developer.microsoft.com/fluentui#/controls/web)<br>
  _While you can build any kind of UX, if you’re building a SPA that integrates with Microsoft 365, it would be easier to use for your users if the UX was the same as other products in Microsoft 365. Fluent UI React compliments MGT with additional controls._

## API SDK

You'll need these SDKs to communicate with APIs used by your app.

- [Microsoft Graph JS SDK v3](https://www.npmjs.com/package/@microsoft/microsoft-graph-client)<br>
  _JavaScript SDK to call Microsoft Graph which is the API to access data stored in Microsoft 365._
- [Microsoft Graph TypeScript Types v3](https://www.npmjs.com/package/@microsoft/microsoft-graph-types)<br>
  _TypeScript types for working with Microsoft Graph that give you design-time type safety in your project._

## Identity SDK

Here are the SDKs that you'll need to implement authentication in your app and be able to connect to Microsoft 365.

- [MSAL2 Provider (included in MGT)](https://docs.microsoft.com/graph/toolkit/providers/msal2)<br>
  _Authentication provider for MGT that facilitates authentication using the Microsoft identity platform_

## API

You'll use the following APIs in your app.

- [Microsoft Graph](https://docs.microsoft.com/graph/overview)<br>
  _The API to access data stored in Microsoft 365_

## Resources

### Learn

Resources on Microsoft Learn that teach you in a structured way how to build this type of app.

- [Develop apps with the Microsoft Graph Toolkit](https://docs.microsoft.com/learn/paths/m365-msgraph-toolkit/)<br>
  _Learning path that explains what the Microsoft Graph Toolkit is and how you can use it effectively to build web apps connected to Microsoft 365._

### Tutorials

Tutorials that you can follow to learn how to build this type of app step by step.

- [Use the Microsoft Graph Toolkit with React](https://docs.microsoft.com/graph/toolkit/get-started/use-toolkit-with-react)<br>
  _Step-by-step tutorial that shows how to use MGT with React web apps_

### Videos

Here are the videos that demonstrate some of the concepts used in this app.

- [Getting started with the Microsoft Graph Toolkit](https://www.youtube.com/watch?v=oZCGb2MMxa0)<br>
  _Short video explaining what Microsoft Graph Toolkit is and how to get started using it_

### Docs

Official documentation from Microsoft relevant to this type of app.

- [Microsoft Graph Toolkit (MGT)](https://docs.microsoft.com/graph/toolkit/overview)<br>
  _MGT documentation explaining what MGT is, how it works and how to use its different features_

### Feedback

Here's where you can submit feedback, and suggestions for new features.

- [Microsoft Graph Toolkit](https://aka.ms/mgt)<br>
  _Submit issues in this GitHub repository where MGT is managed and developed_
- [Microsoft Graph](https://docs.microsoft.com/answers/products/graph)<br>
  _Go here to share feedback and feature ideas for Microsoft Graph with Microsoft_
