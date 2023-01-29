# Just Another Text Editor (JATE)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)




[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


  ---
  ## Description
This is a single-page text editor that runs in a browser and meets the PWA criteria. It features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application is deployed on Heroku and also functions offline. It has the following interface:

![Screen Shot](/assets/00-demo.gif)


[A deployed version can be viewed here.](https://jate-kokkonut.herokuapp.com/)

See the application's GitHub repository [here.](https://github.com/Kokkonut/txt-editor-pwa)

  ---
  ## Table of Contents
  1. [Title](#title)
  2. [Description](#description)
  3. [Installation](#installation)
  4. [Usage](#usage)
  5. [License](#license)
  6. [Contributing](#contributing)
  7. [Tests](#tests)
  8. [Credits](#credits)
  9. [Author](#author)
  10. [Questions](#questions)
  
  ---
  ## Installation
  Clone my repository on GitHub.
  
  To install the application's `dependencies` and `devDependencies`, run:
  ```
  npm install
  ```
  
  To invoke the application, run:
  ```
  npm run start
  ```
  
  ---
  ## Usage
  Please see the video and screenshots.
  
  ### Features and Functionalities
  
  This application is developed to allow users to create notes or code snippets with or without an internet connection, so users can reliably retrieve them for later use. It follows the features and functionalities required in the Assignment's README:
  
  1. When the user opens the application in the user's editor, the user will see a client server folder structure.
  
  2. When the user runs `npm run start` from the root directory, the application starts up the backend and serve the client.
  
  3. When the user runs the text editor application from my terminal, the user will find that the application's JavaScript files have been bundled using webpack.
  
  4. When the user runs the webpack plugins, the user will find a generated HTML file, service worker, and a manifest file.
  
  5. When the user uses next-gen JavaScript in the application, the text editor still functions in the browser without errors.
  
  6. When the user opens the text editor, the user will find the IndexedDB has immediately created a database storage.
  
  7. When the user enters content and subsequently clicks off of the DOM window, the content in the text editor is saved with IndexedDB.
  
  8. When the user reopens the text editor after closing it, the content in the text editor has been retrieved from the IndexedDB.
  
  9. When the user clicks on the Install button, the application is downloaded as an icon on the user's desktop.

  10. When the user loads the application, the user can register a service worker using workbox.

  11. When the user registers a service worker, the user's static assets are pre cached upon loading along with subsequent pages and static assets. 
  
  13. When the user deploys to Heroku, the user has a proper build scripts for a webpack application. 

  ---
  ## License
  License used for this project - MIT
  
  For more information on the above license and other license types, please see the following websites:  
  - [Open Source Initiative](https://opensource.org/licenses)
  - [Choose a License](https://choosealicense.com/)

  ---
  ## Contributing
  To contribute to this application: 
  Please email the author for guidelines.

  ---
  ## Tests
  During development, the application is tested using `localhost`.

  ---
  ## Credits
  The following people/resources were consulted and/or utilized in the development of this application:
  
  * Unit 19 PWA reading materials, videos, and internet resources.
  * Coding Bootcamp Heroku Deployment Guide
  * [Troubleshooting Node.js Deploys](https://devcenter.heroku.com/articles/troubleshooting-node-deploys)
  * [Stackoverflow](https://stackoverflow.com) for troubleshooting Heroku deployment

  ---
  ## Author
  Nicoolas Fraenkel

  ---
  ## Questions
  For questions or issues, please contact: 
  - Nicolas Fraenkel
  - Email: nicfraenkel@gmail.com
  - GitHub Username: Kokkonut
  - GitHub Profile: https://github.com/Kokkonut

  ---

  ## My Git

[![Kokkonut's github stats](https://github-readme-stats.vercel.app/api?username=Kokkonut&theme=blue-green)](https://github.com/Kokkonut/github-readme-stats)

[![Kokkonut's top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Kokkonut&theme=blue-green)](https://github.com/Kokkonut/github-readme-stats)
