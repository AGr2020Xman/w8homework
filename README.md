# README.md Generator: Node.js and ES6+

## Description 

  
Every github project needs a quality README with information about the app - what the app is for, how to use the app, how to install it, how to report issues, and how to make contributions so that developers of all kinds  are more likely to use and contribute to the success of the project. 

This application is a command-line project that runs with Node.js that will dynamically generate a README.md file based on input about your project. Check out the [`ExampleREADME.md`](https://github.com/Michaelmw17/w8homework) in this repo as an example. 


## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Methodology](#methodology)
* [License](#license)
  

## Installation

*Steps required to install project and how to get the development environment running:*

To generate your own README, first run `npm install` in order to install the following npm package dependencies as specified in the `package.json`:
  * [`inquirer`](https://www.npmjs.com/package/inquirer) that will prompt you for your inputs from the command line 
  * [`axios`](https://www.npmjs.com/package/axios) to fetch your info from the GitHub API

The application itself can be invoked with `node index.js`.


## Usage 

*Instructions and examples for use:*



## Methodology

The application utilizes modularization by separating the GitHub API call and generation of the markdown into separate modules: `script.js` and `generateMarkdown.js`, respectively, inside the `utils` folder.

The application also utilizes, as much as i could, syntax introduced in ES6 and beyond, including `let`, `const`,`arrow functions`, template literals, and `async/await`as well as  handling `inquirer`, `axios`, and `fs.writeFile` promises.


## License

Unlicensed 

---

## Questions?

![Developer Profile Picture](https://github.com/Michaelmw17) 

Feel free to use for you own work to generate a README for your project.

GitHub: [@michaelmw17](https://github.com/Michaelmw17/w8homework)

Email: michaelmw17@outlook.com