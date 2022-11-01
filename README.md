# Verademo for Azure DevOps

## Project Description

This application repository was created to illustrate how to properly use Veracode Analysis tools within the a Software Development Lifecycle (SDLC). The examples illustrated here utilize the concept of separation of concerns for CI/CD administration.

The Verademo application example is a simple .NET Core web application with a Angular Front End. In this example both the front end content and simple back end content are bother submitted to the same application portfolio. In a larger application these should be further distributed out into more application portfolios.

>[!NOTE]
>The demo application does not have any major weaknesses or vulnerabilities reported within the main branch. As the purpose of this project is to illustrate integration of the Veracode Tools.

## Pipeline Activity

Pipeline | Script | Status
------ | ------   |----
Scheduled Daily Release Candidate Build from Main branch| azure-scheduled.yml | [![Build Status](https://dev.azure.com/veracode-demonstration/verademo-azure/_apis/build/status/Scheduled%20Daily%20Release%20Candidate%20Build%20from%20Main?repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)](https://dev.azure.com/veracode-demonstration/verademo-azure/_build/latest?definitionId=16&repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)
Pull Request    | azure-pull-request.yml|   [![Build Status](https://dev.azure.com/veracode-demonstration/verademo-azure/_apis/build/status/Pull%20Request%20Pipeline?repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)](https://dev.azure.com/veracode-demonstration/verademo-azure/_build/latest?definitionId=18&repoName=dmedeiros-veracode%2Fverademo-azure&branchName=main)
Pull Request (Dynamic)    |  Experimental |   [![Build Status](https://dev.azure.com/veracode-demonstration/verademo-azure/_apis/build/status/Pull%20Request%20Pipeline?repoName=dmedeiros-veracode%2Fverademo-azure&branchName=development)](https://dev.azure.com/veracode-demonstration/verademo-azure/_build/latest?definitionId=18&repoName=dmedeiros-veracode%2Fverademo-azure&branchName=$(Build.SourceBranchName))

# Pipeline Examples

The examples for the pipelines within the main line branch are only a demonstration of a successful path through the SDLC in each case. The Verademo application within this branch does not container any weaknesses or vulnerabilities to demonstrate any strategy.

# Setup and Usage

#### SAST Plarform/Sandbox Analysis
In the Azure Domain Settings under Service Connection create a Veracode Analysis Center 
Service Connection


#### SAST Pipeline Analysis
In the Azure Project Library

VERACODE_API_ID
VERACODE_API_KEY




#### SCA Agent
SRCCLR_API_TOKEN Set to the token value

The sample application

## Service Connection

Veracode SaaS Connection == id key
dmedeiros-veracode

azure-scheduled-pipeline.yml
azure-pull-request.pipelines.yml

# Azure DevOps Pipeline as Code

The sample scripts ei

[Azure DevOps Script Repository](https://github.com/dmedeiros-veracode/devops-scripts-azure-devops.git)


https://dev.azure.com/veracode-demonstration/verademo-azure
