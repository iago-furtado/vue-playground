# Vue.js Project Setup Guide

## References:
1. [Vue.js Tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/vuejs-tutorial)

## Step 1: Check Node.js and npm

- Open a terminal or command prompt.
- Run the following commands to verify that Node.js and npm are installed:
```
  node -v
  npm -v
  npm install
```
- These commands should display the installed versions of Node.js and npm.

## Step 2: Install Vue CLI

- Open a terminal.
- Run the following command to install the Vue CLI globally:
```
  npm install -g @vue/cli
```
- This installs the Vue CLI globally on your machine.
## Step 3: Create a Vue Project

Now that you have Vue CLI installed, you can create a new Vue.js project.

### Create a Vue Project:

- In the terminal, navigate to the directory where you want to create your project.
- Run the following command to create a new Vue project (replace "my-vue-project" with your preferred project name):
```
  vue create my-project
```
- Choose the default option for Vue 3.

- Quickly run your Vue application by navigating to the new folder and typing npm run serve to start the web server and open the application in a browser:
```
  cd my-project
  npm run serve
```
- You should see "Welcome to your Vue.js App" on http://localhost:8080 in your browser. You can press Ctrl+C to stop the vue-cli-service server.

## Step 3: Install VS Code Extensions

- **Vetur Extension:**
  The Vetur extension supplies Vue.js language features (syntax highlighting, IntelliSense, snippets, formatting) to VS Code.



## Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
