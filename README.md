# cypress_cucumber_v12.10
Testing in Cypress v12 with BDD and HTML report

Testing Framework with Cypress V12 + Cucumber and BDD-HTML Report

To structure, install nodeJs and dependencies with: `npm install`
![image](https://user-images.githubusercontent.com/33332202/234979603-787341db-bd09-4636-bbe1-46485b25b033.png)


To run the tests use: `npm test`
![image](https://user-images.githubusercontent.com/33332202/234979796-683833ca-cd16-467a-8596-53aa5908ae28.png)


At the end of the test, the HTML report opens in your browser:
![image](https://user-images.githubusercontent.com/33332202/234980006-c9a4203c-221b-4f46-ba79-9a156cd06af5.png)


And to analyze manually with Cypres use the command: `npx cypress open`

SOME BASIC GUIDELINES:

>  BDD FILES (FEATURES) MUST BE BUILT IN THE `cypress\e2e\features` FOLDER WITH THE `*.feature EXTENSION

> THE "STEPS" FILES MUST BE DEVELOPED IN THE `cypress\support\steps` FOLDER

> YOU CAN CREATE SUPPORT CLASSES FOR THE STEPS FILES IN THE `cypress\support\pageObjects` FOLDER AND USE CUSTOM OBJECTS TO FACILITATE THE MAINTENANCE AND REUSE OF YOUR AUTOMATIONS.

More information about Cypress at https://docs.cypress.io/guides/overview/why-cypress
