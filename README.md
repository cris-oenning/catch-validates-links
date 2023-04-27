# Link Collection and Validation System

This script uses JavaScript technology and Node.Js to collect and validate links through standardized text, which can be modified as needed.

# How the System Works:

It is a fully functional library that can be called through the terminal, where we have developed commands for this, such as "npm run cli" to bring the list of links from inside the texto.md file, located in the files folder, or npm run cli :validate to bring the list of links validated through HTTP requests and responses/codes.

# O que foi trabalhado no sistema:

* Exports and imports of modules through the keywords "export" and "import".

* We manipulate the code with Lib File System of Node.Js both to read files, as well as to get the status of links to know if we are working with directories or files so that our code can branch and execute logical parts for each case.

* We create our own terminal commands, including our own scripts in the package.json file.

* We work with promises in JavaScript, specifically with promise objects, async, await, then and asynchronous code.

* We created regular expression, which are patterns to be used in strings and characters, creating a specific regular expression for the current need, which was to identify character patterns in one or more texts.

* We work with HTTP requests through the native API of Node.Js (from version 18) which is the Fetch API, working with responses that are a promise and resolving them, also working with promise.all to resolve a list of several promises bringing the return of these, among other small JavaScript details.

* We use the Try/Catch block to handle errors, like JavaScript error object methods.

# How to use:

Requires Node.Js version 18 (or higher) installed. -> https://nodejs.org/
You need to have the Chalk library installed.

1. Install Node.Js 18 (or higher) from the official website https://nodejs.org/, if not installed.
2. Install Chalk library by command in terminal "npm i chalk"
3. Put your text for searching and validating links in the texto.md file located in the files folder
4. Manipulate your regular expression as per your need in code line number 5 (const regex)
5. If you don't have a ready expression, you can build it according to your needs in https://regex101.com/
6. In the terminal, type "npm run cli" for link search
7. In the terminal, type "npm run cli:valida" for link validation via HTTP request and response.

# Observation:

The system already has a text and regular expression ready as an example.
basta você digitar no terminal os comandos abaixo para verificar como funciona o sistema como exemplo:

* Link search command: npm run cli
* Link validation command: npm run cli:valida 

# Expansion:

With this code base, you can further expand the features of this Lib, as we will always have features to add and refine errors, tests, creating your own features depending on your needs.