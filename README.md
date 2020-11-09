# :evergreen_tree: Cypress Testing Training

> ### *“All code is guilty, until proven innocent.”* – Anonymous
<br>

## :eyes: Overview
It is always safer to test our code than to simply assume that everything is working. The price of shipping faulty software is too big compared to the investment of time that testing requires. However, this investment don't need to be greater than necessary. Automated testing is a reliable and efficient way to optimize our time as developers and guarantee that we are always shipping working code to our clients.

In this training, you will learn the first steps of setting up the E2E testing tool [Cypress](https://www.cypress.io/) in your front-end applications. By the end of this session you should feel comfortable installing and working with basic Cypress functionalities, writing simple test cases, and running tests tests on your application.

**Here are a few resources to help get you started:**
 - [Introduction to Cypress](https://docs.cypress.io/guides/core-concepts/introduction-to-cypress.html#Cypress-Can-Be-Simple-Sometimes)
 - [Cypress in a Nutshell](https://www.youtube.com/watch?reload=9&v=LcGHiFnBh3Y)
 - [How to Test Your Frontend with the Cypress.io Framework](https://medium.com/free-code-camp/how-to-test-your-frontend-with-the-cypress-io-framework-f048070f4330)
 - [Testing Tips](./testing-tips.md)

This repository contains a simple to-do web application developed with ReactJS that you will use to run your tests against. The principles of what you will learn should work with any front-end frameworks.

 ## Instructions

During the training I will walk you through setting up Cypress and writing your first test cases. If you get lost, please refer to this section. All information you need will be found here.

### **Setting up project repository**.

Fork this repository so you can have a copy saved to your GitHub that you can work on. Please, do not sync your fork with this repository. If you do not know how to fork GitHub repositories, check this page: [Fork a repo](https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/fork-a-repo).

Clone your fork to your local machine. For the purposes of this training, I advise you to clone your project into a windows directory and not into a WSL directory (if you use WSL at all). Unfortunately, WSL only supports cypress headless mode. There are a few workarounds to make the cypress UI work in WSL that will not be covered in this training.

After you sucessfully cloned your forked repository run: `npm i` or `yarn` (this project uses yarn, but running an npm command should work just fine).

### **Installing and setting up Cypress**

To start the application all you need to do is run `npm start` or `yarn start`. It then will available locally at `http://localhost:3000`. It should look something like this:

<img src="./assets/todo-testing.gif" style="display:block; width:50%; margin: 20px auto; border-radius: 8px; border: 2px solid #333">

Now that our app is working, let's focus in setting up cypress. Run `npm i cypress` or `yarn add cypress`.
