# Text_Editor_PWA-19

## Description
This app is a text editor that runs in the browser. It is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline. To build this text editor, I started with an existing application and implement methods for getting and storing data to an IndexedDB database. I used a package called idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

## Criteria
* By opening the application in the editor, you should see a client server folder structure
* By running `npm run start` from the root directory, you find that the application should start up the backend and serve the client
* By running the text editor application from the terminal, you find that the JavaScript files have been bundled using webpack
* By running the webpack plugins, you find that you have a generated HTML file, service worker, and a manifest file
* By using next-gen JavaScript in the application, you find that the text editor still functions in the browser without errors
* By opening the text editor, you find that IndexedDB has immediately created a database storage
* By entering content and subsequently click off of the DOM window, you find that the content in the text editor has been saved with IndexedDB
* By reopening the text editor after closing it, you find that the content in the text editor has been retrieved from our IndexedDB
* By clicking on the Install button, you download the web application as an icon on your desktop
* By loading the web application, you should have a registered service worker using workbox
* By registering a service worker, you should have the static assets pre cached upon loading along with subsequent pages and static assets

## Link
[Heroku Deployed Page](https://text-editor-hw.herokuapp.com/)
