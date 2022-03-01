  <p align="center">
  <img src="images/logo.png">
</p>

  # J.A.T.E Text Editor

  ## Description

  This application is a single page text editor where you can add notes and keep track of things. It follows PWA structure, which allows it to be installed into a user's system at any time.

  ## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Licensing](#licensing)
  - [Contributing](#contributing)
  - [Testing](#testing)
  - [Contact](#contact)

  ## Installation
  To install, the user can go to the deployed application and can install the program directly from their browser by pressing the install button on the top left, or by using the in-browser installation button on the right side of the URL bar.

  ## Licensing
  Distributed under MIT licensing. 

  ## Contributing
  New users can contribute to the project by cloning the repository and adding new features onto the code established by the project. 

  ## Testing
  nmp test

  ## Contact
  If you have any questions regarding this project, feel free to contact me directly at aborgescolon@gmail.com, or on my GitHub at https://github.com/xndrbrgs.


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