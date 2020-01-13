# Deploy a Containerized Application
An interview exercise for DevOps candidates.

## Goals
The goals of the exercise are the following

1. to show that candidates are hands on and can write code that builds and runs an application in the cloud
2. to show that candidates can think about problems holisticly
3. to have a vehicle for a deeper discussion in a face to face interview setting 

## Overview
The outcome of this exercise, is to create an automated series of steps for building and deploying a sample application into the AWS Cloud.

## What to Submit
- A zip file or link to a github repository with code that accomplishes the following: 
  - Builds a container that successfully runs the [sample application](sample application).
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
- Take the [](TODO: LINK TO SAMPLE APP) and create a Dockerfile for it, capable of running it in a production capacity within AWS.
  - TODO: DEFINE WHAT "running" means based on the application.
- Automate deploying your containerized application to the AWS service of your choice.
- Automate setting up the hosting environment for your application.
- Create a test command/script capable of verifying that the application is up and running as expected.


## Questions (to facilitate discussion when we get together):
- How did you choose to bootstrap your hosting environment?
- What balance did you strike between hosted AWS services, and self-managed components?
- How would you monitor this application?  What metrics would you monitor?
- Could you extend your solution to launch a secure cluster of this application?  What would need to change to support this use case?
- Could you extend your solution to replace a running instance of the application with little or no downtime?  How?
- What would you do if you had more time?
