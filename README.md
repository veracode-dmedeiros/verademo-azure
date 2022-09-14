# Verademo for Azure DevOps

## Project Description
This application repository was created to illustrate how to properly use Veracode Analysis tools within the a Software Development Lifecycle (SDLC). The examples illustrated here utilize the concept of seperation of concerns for CI/CD adminstration. 

The Verademo application example is a simple .NET Core web application with a Angular Front End. That currently does not have any major weakensses or vulnerablities within the main branch.

## Pipeline Activity
Pipeline | Script | Status
------ | ------   |----
Scheduled Daily Release Candidate Build from Main| azure-scheduled.yml | [![Build Status](https://dev.azure.com/veracode-demonstration/verademo-azure/_apis/build/status/Scheduled%20Daily%20Release%20Candidate%20Build%20from%20Main?repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)](https://dev.azure.com/veracode-demonstration/verademo-azure/_build/latest?definitionId=16&repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)
Pull Request    | azure-pull-request.yml|   
Release Cadidate     |       

# Pipeline Examples
The examples for the pipelines within the main line branch are only a demonstration of a successful path throught the SDLC in each case. The Verademo application within this branch does not container any weaknesses or vulnerablities to demonstrate any strategy.

# Setup and Usage
The sample application 

## Service Connection
Veracode SaaS Connection == id key
dmedeiros-veracode



azure-scheuled-pipeline.yml
azure-pull-request.pipelines.yml






# Azure DevOps Pipeline as Code
The sample scripts ei

[Azure DevOps Script Repository](https://github.com/dmedeiros-veracode/devops-scripts-azure-devops.git)