# docsify documentation site generator

## Quick Start
This document is using [docsify](https://docsify.js.org/) to create.

---

## docsify installation

    npm i docsify-cli -g

## or update docsify

    npm i -g docsify-cli

Current project is using version docsify-cli@4.4.0

---
## Initialize the project

    docsify init ./docs


---
## Live Preview

    docsify serve docs

## Install docsify-sidebar-collapse Plugin

    npm i docsify-sidebar-collapse --save

Add it to index.html
```html
    <script src="//unpkg.com/docsify-sidebar-collapse/dist/docsify-sidebar-collapse.min.js">
```


---
## Initialize Firebase
The document is hosting in Firebase. We need to have a Google Account then initialize the Firebase.

[Firebase Hosting Document](https://docsify.js.org/#/deploy?id=firebase-hosting)

[Firebase CLI Reference](https://firebase.google.com/docs/cli/)

If you didn't install firebase-cli, install it:

    npm install -g firebase-tools

The Google Account of the use handbook hosting (We use the DQ Dev account to host all projects of user handbooks):

    https://firebase.google.com/
    User: designquest.dev@gmail.com
    Password: JK6162jk66

Craete a new project in the Frebase account to host the user handbook.

Back to Terminal, logout your current Google account then login to the project google account and init the project

    firebase logout
    firebase login 
    > use designquest.dev@gmail.com
    firebase init
    > Hosting: Configure and deploy Firebase Hosting sites
    > Select the project you created in the Firebase    

Edit the firebase.json

    "public": "docs",

## Deploy to Firebase
After login, you can deploy the document to Firebase

    firebase deploy


