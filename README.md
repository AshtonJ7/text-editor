# Text Editor

This is a text editor that runs in the browser. This app is a single-page application that meets the criteria for a progressive web application.

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
## Features

- Stores data to an IndexedDB database
- Fullscreen mode
- Downloadable

## Tech Stack

**Server:** Node, Nodemon, Express

- Webpack
- Code-mirror-themes
- Service Worker API
- IndexedDB API
- 
## Link

https://peaceful-stream-63675-161d7f225d28.herokuapp.com/

## Screenshots

![2](https://github.com/AshtonJ7/text-editor/assets/62944042/31f250e7-9a77-464c-ab1d-e0139c5b18c8)

