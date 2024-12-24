# GraphQL WebSocket Practice Chat App

This project is a practice chat application built with GraphQL and WebSocket subscriptions. The app demonstrates real-time messaging using GraphQL subscriptions, queries, and mutations.

---

## Features

- **GraphQL Subscriptions**: Real-time messaging functionality using WebSocket connections.
- **GraphQL Queries and Mutations**: Fetching and posting messages.
- **WebSocket Integration**: Updates all connected clients immediately when new messages are sent.

---

## Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

---
## Folder Structure
```
client/
├── node_modules/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Chat.js
│   │   ├── LoginForm.js
│   │   ├── MessageInput.js
│   │   ├── MessageList.js
│   │   └── NavBar.js
│   ├── lib/
│   │   ├── graphql/
│   │   │   ├── client.js
│   │   │   ├── hooks.js
│   │   │   └── queries.js
│   │   └── auth.js
│   ├── App.js
│   ├── index.js
│   └── style.css
├── .gitignore
├── package-lock.json
└── package.json

server/
├── data/
│   └── db.sqlite3
├── db/
│   ├── connection.js
│   ├── ids.js
│   ├── messages.js
│   └── users.js
├── node_modules/
├── scripts/
│   └── create-db.js
├── .gitignore
├── auth.js
├── package-lock.json
├── package.json
├── resolvers.js
├── schema.graphql
└── server.js
```