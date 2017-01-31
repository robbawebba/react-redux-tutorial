# Dev Environment Walkthrough
Loosely following [this tutorial](https://www.codementor.io/tamizhvendan/beginner-guide-setup-reactjs-environment-npm-babel-6-webpack-du107r9zr)

Finished product here (just for reference): https://github.com/robbawebba/barebones-react-starter

## Big Picture Topics:
* Webpack (the bundler)
* babel (the transpiler)
* webpack-dev-server (local dev server)
* file structure 

## Software Requirements
#### Node & npm
* Mac:
  * Install [Homebrew](http://brew.sh/) 
  
    ```
    /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
    ```

  * run `brew update` twice to verify installation
  * `brew install node`
  * `node -v` and `npm -v` to verify installation

* Windows:
  * Go to [Node.JS Website](https://nodejs.org/en/download/current/) and download/run the installer (.msi)
  * `node -v` and `npm -v` to verify installation

## Starting our NPM proxject
Let's create a new project directory and initialize it as an npm package.
    
  ```
  mkdir to-do
  cd to-do
  npm init
  ```

* Open the directory in the editor of your choice to get started
* Take a look at the new file `package.json`. This file defines our project and all of its dependencies

## Using Webpack to Bundle Our JS
## Adding Babel Loader to transpile ES6 and JSX
![Babel diagram](https://www.filepicker.io/api/file/uwXkbHtfRzueOW9FZOaP)
## Adding Some React
## Creating a Tricked Out Dev Environment

# Creating our To-do App (React)

# Adding Redux to Manage our App's State

# Connecting Redux to an API

