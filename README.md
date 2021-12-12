Building a CI/CD Pipeline is a project that combines Agile Planning, Continous Integration, and Continous Delivery concepts. A quarterly and a yearly plans are created in a Spreadsheet as a part of Agile Planning to help managing project. To help with project tracking, all tasks are mapped on tickets with expected start and end dates and are categorized in three sections: To Do, In Progress, and Done. For this project, Azure Cloud Shell is used. Inside of the environment, a scaffolding code was created. Scaffolding code consists of a: 
* Makefile that executes instalation of required packages, code testing step, and a linter step
* requirements.txt file that contains all required packages that are going to be installed on a environment in a install step of a Makefile
* Python script code
* Python script that contains tests for a code  

The next step was to configure GitHub Actions to provide Continous Integrations step and verify remote teests pass. Continuous Delivery was set up by using Azure Pipelines and Azure App Service. The final product of a project is a Flask Machine Learning web application deployed on a Azure Pipelines.  
Finally, this project is documented in two steps:
1. README.md file - file containing basic informations how to run a project and output screenshots of project outputs.
2. Demo video file where the project is presented step-by-step.

## Project Plan

* A link to a Trello board for the project: https://trello.com/b/3OUrdavt/building-ci-cd-pipeline
* A link to a spreadsheet that includes the original and final project plan>: https://docs.google.com/spreadsheets/d/1M0sbWKSYJlzaEH8bg0qZeEOm8pyYqbTUzcHVhljJldw/edit#gid=1348135932

## Instructions

<TODO:  
* Architectural Diagram (Shows how key parts of the system work)>

<TODO:  Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


