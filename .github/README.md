# Project Name

>Badges are linked to the build and deployment runs in this repository using GitHub actions. Replace ORG and REPO with this projects org and repo. The badges correspond to the `workflows/name_of_workflow` in the url. If you change a name of the workflow, you'll also need to change it in the badges url.
![](https://github.com/ORG/REPO/workflows/Production%20Build/badge.svg) ![](https://github.com/ORG/REPO/workflows/Development%20Build/badge.svg) ![](https://github.com/ORG/REPO/workflows/Cargo%20Security%20Audit/badge.svg) ![](https://github.com/ORG/REPO/workflows/Testing/badge.svg) 

## Overview

This is a general overview of your project. Everything in this short paragraph should state the purpose of the repository.

## Installation

Provide installations instructions.

- How do I get the application
- What steps to I need to take to make it usable
- Common issues with the installation

## Usage

Instructions on how to use the application once it is properly installed.

- General overview of the command
- Output from the help option
- Example uses of the command for common situations

## Architecture

Give an architecture overview of your project with use cases. You could just give use cases here as well. Tables are an effective way describing your use cases in a short consise manner. Diagrams will help others visualize your solution. 

**Example:**
>This application can be used in a few different architectures, depending on the use case.
>
>| Architecture | Use case |
>|----------|-------------|
>|Lambda|Syncing small files (<500MB)
>|EC2 + Large EBS volume|Syncing large files (>500MB)
>
>### Lambda
>
>For smaller files that need to be sync'd between two buckets we can use an AWS Lambda to run the application.
>
>#### Benefits
>
>- Don't have to provision an EC2 instance
>- Only running when something needs to be sync'd
>- Limited attack surface
>- Only pay for the runtime of the Lambda + transfer cost
>
>#### Diagram
>
>### EC2 Instance + Large EBS Volume
>
>Used when you need to sync large files or AMI's. The attached EBS volume needs to have sufficient space to store the artifacts while they are being sync'd.
>
>#### Benefits
>
>- Can sync large files
>- Control the amount of space that you need for the EBS volume
>- Not limited 15 minutes of activity
>
>#### Diagram

## Licenses

Short paragraph about what the project can and can't be used for. A list of any licenses that are attached to the project.