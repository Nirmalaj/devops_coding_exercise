# devops_coding_exercise
An exercise for devops candidates.

The goals of the exercise are the following

1. to show that the candidate is hands on and can write code that builds a cloud-hosted instance

2. to show that candidates can think about big picture topics like security

3. to give us a vehicle for a deeper discussion in a face to face interview setting 

Build a Secure Cloud ElasticSearch Instance

The purpose of this exercise is to demonstrate that you can write code that launches a virtual machine on Amazon Web Services running a secure ElasticSearch service.

The output of this exercise should be the following:

- Code that can bring up an AWS instance, install ElasticSearch in a secure way, and prove that it is functioning.
- A README file with at least the following information
    - instructions that allow us to run your code
    - a description of your solution noting interesting choices you made and why you made them
    - a list of resources you consulted to accomplish the exercise
    - feedback on the exercise and some information about how long you spent on it

The requirements of the exercise are the following:
- Must use AWS.  The AWS free tier should be sufficient.  If your ideal solution would use additional services please include that information in your README
- ElasticSearch access and communication must be secure.

Bonus:
Can you extend your code to create a cluster of 3 ElasticSearch nodes?  HINT: You will need to look at the AWS Cloud Plugin for ElasticSearch.

Questions (to facilitate discussion when we get together):
- How did you choose to automate the provisioning and bootstrapping of the instance?  Why?
- How did you choose to secure ElasticSearch?  Why?
- How would you monitor this instance?  What metrics would you monitor?
- Could you extend your solution to launch a secure cluster of ElasticSearch nodes?  What would need to change to support this use case?
- Could you extend your solution to replace a running ElasticSearch instance with little or no downtime?  How?
- Was it a priority to make your code well structured, extensible, and reusable?
- What sacrifices did you make due to time?
