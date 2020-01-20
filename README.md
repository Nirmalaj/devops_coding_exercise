# Deploy a Containerized Application
An interview exercise for DevOps candidates.

## Goals
The goals of the exercise are the following

1. to show that candidates are hands on and can write code that builds and runs an application in the cloud
2. to show that candidates can think about problems holisticly
3. to have a vehicle for a deeper discussion in a face to face interview setting 

## Overview
The outcome of this exercise is an automated series of steps for building and deploying a sample application into the AWS Cloud.

## What to Submit
- A zip file or link to a github repository with code that accomplishes the following: 
  - Builds a container that successfully runs the [https://github.com/salsify/gifmachine](Sample Application).
  - Creates a runtime environment within AWS to host the application
  - Runs a test that validates the application is up and running as expected
- A README file with at least the following information
    - Instructions that allow us to run your code
    - A description of your solution noting interesting choices you made and why you made them
    - A list of resources you consulted to accomplish the exercise
    - Feedback on the exercise and some information about how long you spent on it

## Requirements
The requirements of the exercise are the following:
- Must use AWS.  The AWS free tier should be sufficient.  If your ideal solution would use additional paid services please include that information in your README
- Take the [https://github.com/salsify/gifmachine](Sample Application) and create a Dockerfile for it, capable of running it within AWS.
  - Successfully able to accept the expected (as per the README of the application) http requests, and display them to clients.
  - Able to connect to a running database.
  - Available via the internet.
- Automate deploying your containerized application to the AWS service of your choice.
- Automate setting up the hosting environment for your application.
  - This *does not* require automation for setting up and configuring the database required by the application. That can be configured out-of-band in whatever means you find reasonable (RDS is one straightforward option).
- Create a test command/script capable of verifying that the application is up and running as expected.


## Questions we will likely cover later:
- How did you choose to bootstrap your hosting environment?
- What balance did you strike between hosted AWS services, and self-managed components?
- How would you monitor this application?  What metrics would you monitor?
- Could you extend your solution to launch a secure cluster of this application?  What would need to change to support this use case?
- Could you extend your solution to replace a running instance of the application with little or no downtime?  How?
- What would you do if you had more time?
