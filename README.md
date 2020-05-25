# cucumber-cypress-ts
Cucumber and Cypress integration with TypeScript

> In this tutorial we'll learn how to use Cucumber, Cypress and TypeScript togther for automated acceptance testing of a React ToDO App

## Contents

* [Installation](#installation)

## Installation

* To get started, we'll create a new folder named __cucumber-cypress-ts__ and move into that directory:

    ```
    mkdir cucumber-cypress-ts
    cd cucumber-cypress-ts
    ```

* Next, initialize it as an npm project:

    ```
    npm init
    ```

    After running npm init, we'll need to supply npm with information about our project. We can let npm assume sensible defaults, then we can add the y flag to skip the prompts for additional information:

    ```
    npm init -y
    ```

Now that our project space is set up, we're ready to move on to install the necessary dependencies.

### Installing Dependencies

* With a bare npm project initialized, the next step is to install the dependencies that are required to run TypeScript.

    Run the following commands from our project directory to install the dependencies:

    ```
    npm install typescript
    npm install tsify
    ```
* Next, install __Cypress__ and __Cypress Cucumber Preprocessor__. This will add the Cypress and Cucumber support to the project:

    ```
    npm install cypress
    npm install cypress-cucumber-preprocessor
    ```




