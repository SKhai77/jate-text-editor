# Progressive Web Applications: JATE Text Editor
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)


## Description

The purpose of this project is to build a single-page text editor application that runs in the browser that meets the PWA criteria. Additionally, it featured a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The applications also function offline.

When building this text editor, I started with an existing application and implemented methods for getting and storing data to an IndexedDB database. I used a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla. Then, I deployed this full-stack application to Heroku.


## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)


## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## Technologies

- Express.js
- Heroku
- IndexedDB API
- JavaScript
- JSON
- Node.js 
- NPM 
- Service Worker API
- Webpack


## Installation

In order to be able to run the applicaton, you are required to do the following:

- Download the zip file/ clone the GitHub repo 
- Open the folder in VSCode
- Click the "Toggle Panel" on the right-side or "Ctrl+J" to see the Terminal or Command Line Interface(CLI)
- Then, install npm (Node Package Manager) inside the repo by typing the following code in the Command Line:

```
    npm install               Press Enter
```


## Usage

To use the application,
- You need to do, "npm install" if you haven't done in the Installation section above.
- Then, type the following commands in the Command Line:

```
    npm run start               Press Enter
```
- Please refer to the Acceptance Criteria section for the steps to test the app.
- Visit the live website by [clicking here!](https://skhai77-jate-text-editor-7aaafa1ed889.herokuapp.com/)


## License

This project is under the MIT License. [Click here for more information](https://opensource.org/licenses/MIT).