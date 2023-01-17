# Coding assignment

The goal of this coding assignment is to evaluate how you handle a new situation and the style of code you produce.

The objective is to create a UI for a list of GraphQL objects you get from an API.
We will be mostly looking at the UI/UX, but also the code structure.

You should not be working more than a few hours on this. It should not be a fully functional App, but should follow the industry standards for the views you'll be creating.

The assignment requirements are provided in the form of user stories (see below).

The deliverable should be a react-native project written in Typescript. Usage of Expo is optional. You can deliver it in the form you prefer (GitHub, BitBucket, zip file, ...).

## CA-1 - List of documents

As a user
I want to see a list of documents

### Acceptance criteria

- Get the list of documents from the GraphQL API (https://app.st-basquiat.co/graphql/) using the findDemoDocuments query.
- A screen that displays the list of documents.

### Comments

- The service does not need any authentication
- We've created sample data for you. You can make any changes you want.
- Endpoint: https://app.st-basquiat.co/graphql/
- GraphQL Query: findDemoDocuments
- Make it beautiful and engaging!

## CA-2 - Detail of documents

As a user
I want to see a the details of a document

### Acceptance criteria

- A detail view for a document containing title, description, creationDate, updatedDate
- A way to navigate back to the list of document

### Comments

- The service does not need any authentication
- We've created sample data for you. You can make any changes you want.
- Endpoint: https://app.st-basquiat.co/graphql/
- GraphQL Query: findDemoDocuments
- Make it beautiful and engaging!

## CA-3 - Edit document title

As a user
I want to edit the document title and description.

### Acceptance criteria

- The service needs a token Authorization header with the following token: "basquiat-demo-2023-a"
  ```json
  {
      "Authorization": "Token basquiat-demo-2023-a"
  }
  ```

- A screen/view to edit the title and description.
- Edition should be triggered in the list and detail view
- New values written back to the server through the API

### Comments

- Endpoint: https://app.st-basquiat.co/graphql/
- GraphQL Mutation: changeDemoDocument

## Definition of Done

This is the general 'definition of done' for the purpose of this assignment.

- I18N: code is internationalized and localized in 2 language: EN and FR.
- Target platform: iPhone or Android only your choice
