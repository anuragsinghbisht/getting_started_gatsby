# getting_started_gatsby

This project is a tutorial to get started with gatsby, create component pages, build and deploy static site

# How to!
Install the dependencies and devDependencies and start the server.
```sh
$ npm install --save gatsby@next gatsby-link@next
$ ./node_modules/.bin/gatsby develop
```
Create `index.js` in `src\pages` folder
```sh
$ mkdir -p src/pages
```
To build the project after development
```sh
$ gatsby build
$ npm install -g surge
$ surge public/
```

