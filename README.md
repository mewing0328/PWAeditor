# PWAeditor
A single-page application to create notes or code snippets with or without an internet connection.

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description
---
A text editor that runs in the browser. PWAeditor is a single-page application that meets the PWA criteria and features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. 
- The application will also function offline.
- The application uses a package called `idb`, which is a lightweight wrapper around the IndexedDB API. 

## Table of Contents
---
[1. Installation](#installation)

[2. Usage](#usage)

[3. Heroku Link](#heroku-link)

[4. Demo and Screenshots](#demo-and-screenshots)

[5. Contributing](#contributing)

[6. Questions](#questions)

[7. License](#license)

[8. Credits](#credits)

[9. Technical Specifications](#technical-specifications)

## Installation 
---
The application has dependencies (see package.json file). Before using the application, install npm modules.

```bash
npm install
```
## Usage 
---
The application will be invoked by using the following command:

```bash
npm run start dev or npm run start
```
## Heroku Link
---
[Heroku Link for PWAeditor:](https://pwaeditor.herokuapp.com/) 
* is deployed to Heroku at live URL with build scripts
* loads with no errors
* user experience is intuitive and easy to navigate
* user interface style is clean and polished
* resembles the mock-up functionality provided in the Challenge instructions

 ## Demo and Screenshots 
---

1. Demo installing the application from the browser:

    <img src="./Assets/application.gif">

2. Demo utilizing the browser and the application: Uses IndexedDB to create an object store and includes both GET and PUT methods

    <img src="./Assets/demo.gif">


3. Image of the brower website and application open at the same time

    <img src="./Assets/browser_and_application.png">

4. Image of IndexedDB

    <img src="./Assets/idb-storage.png">

5. Image of Manifest

    <img src="./Assets/manifest.png">

6. Image of Service Worker

    <img src="./Assets/service-worker.png">

## Contributing 
---
Contributions are welcomed for future versions with features such as additional enhancements.

For all contributions, please refer to [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) for contributing guidelines.

## Questions
---
Interested in seeing my other work?

Check out my GitHub account: [mewing0328](https://github.com/mewing0328).

If you have additional questions, please reach me at [masandraewing@gmail.com](mailto:masandraewing@gmail.com).

## License 
---
PWAeditor application is covered by MIT license. 

 To view the most current and full license description in opensource.org, click on the license name below.  

 [![MIT}](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Credits
---
Credit for tutorials and guides I utilized in my code

George Washington University - Coding Bootcamp: Repository Lesson 19-PWA
 - Activity 28-Stu_Mini-Project was the majority of what was utilized for examples

[webpack.js.org](https://webpack.js.org/): Documentation for utilizing webpack

## Technical Specifications
---

### PWAeditor application enables a user to:
```
- open the application in my editor THEN see a client server folder structure
- run `npm run start` from the root directory THEN find that the application starts up the backend and serve the client
- run the text editor application from terminal THEN find that JavaScript files have been bundled using webpack
- run webpack plugins THEN finds a generated HTML file, service worker, and a manifest file
- use next-gen JavaScript in my application THEN finda that the text editor still functions in the browser without errors
- open the text editor THEN finds that IndexedDB has immediately created a database storage
- enter content and subsequently click off of the DOM window THEN finds that the content in the text editor has been saved with IndexedDB
- reopen the text editor after closing it THEN finds that the content in the text editor has been retrieved from IndexedDB
- click on the Install button THEN downloads the web application as an icon on desktop
- load the web application THEN has a registered service worker using workbox
- register a service worker THEN has static assets pre cached upon loading along with subsequent pages and static assets
- deploy to Heroku THEN has proper build scripts for a webpack application
```

### PWAeditor also: 
```
- works without an internet connection
- automatically saves content inside the text editor when the DOM window is unfocused
- bundled with webpack
- creates a service worker with workbox that Caches static assets
- uses babel in order to use async / await
- generates `manifest.json` using the `WebpackPwaManifest` plug-in
- can be installed as a Progressive Web Application
```
