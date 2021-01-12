# DevOps Engineer - Coding challenge

## How to participate

1. Read the instructions carefully and do not hesitate to check the **Links and resources** section before you start.
2. Join us in [slack](https://join.slack.com/t/next-media-team/shared_invite/enQtMzM0MjIzNjkyNDUxLTI5ZjhhNTkxZTZiYzdkODIyMDkyZWIyNjFlZTE5MmQzMjNkNzZkOTdmMjcyY2Q1NTZlN2E2NTBkYjk1MGU3Mjk), then join **#tech-challenge** and do not hesitate to address any question, there is no stupid question, we're available to help daily. 
3. When you're ready to start the test, make sure you init a Github repository and share the link by email to **tech-challenge@nextmedia.ma** with the object **Coding Challenge DevOps Engineer application by FirstName LastName**, it'll be considered as the time your started working on the challenge.
4. Once you're done with the test, reply again by email to notify us you're done with it. 

Make sure you spare an **average of 8 hours**, and a **maximum of 8 day** to work on the challenge.

## Content

Build using Ansible a dev environment with:
- An elasticsearch single node with 1 node that can also host kibana
- A logstash instance 
- A web instance for hosting an application that produces logs in a json format

Use Vagrant or docker for providing instances for dev environment

The environment should be multi environments compliant.
 
After having setup the dev environment, init a test environment with a cluster of elasticsearch having 3 nodes:
- node 1 (master & data) + kibana
- node 2 (master & data)
- node 3 (master & data)

#### Notes
- Organize your code, so it's easily maintainable, code is elegant and readable.
- Your solution should be able to handle multi environment.
 
## Technologies to use
- Ansible
- Vagrant or docker

## Evaluation criteria 🚨
- Accuracy to follow instructions.
- Code readability and coding style (PSR).
- Clean commit history in git making code review easy, push progressively instead of pushing the whole project in a single commit.
- Quality of documentation (The readme should be short and concise, like open source projects readme, it should contain all necessary step to build and make the app running.

## Instructions
- Put more focus on code quality and less on speed
- Don't hack something quickly, take your time and craft something clean
- Write a readable and maintainable code
- Subscribe to the repository, so you're notified about any change performed in this test

The goal of this test is more to evaluate the way of thinking, design and quality of code (We accept juniors and seniors). 

## Questions?

If you have any questions, ask directly in our slack, room #tech-challenge.  

## Links & resources
- https://www.ansible.com
- https://www.vagrantup.com
- https://docs.docker.com


That’s it ! May the force be with you !! 🖖 
