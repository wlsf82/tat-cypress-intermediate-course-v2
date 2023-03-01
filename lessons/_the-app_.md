# Getting to know the Application Under Test (AUT)

Before we start configuring Cypress and writing automated test scripts, let's dive a bit into the AUT.

For the TAT School Cypress Intermediate course, we are going to test a complex application. This application is an [_open-source_ version of GitLab, running in a _container_](https://hub.docker.com/r/wlsf82/gitlab-ce) in your local environment.

## Application features

GitLab has many features, however, during this course, we will test the following:

- _Login_
- _Logout_
- Project creation
- _Issue_ creation
- Adding a _label_ to an _issue_
- Adding a _milestone_ to an _issue_
- git clone

## Your challenge

During the course of automated tests with Cypress (intermediate) from the TAT Schools, I challenge you to test all the functionalities listed above, both via API (_Application Programming Interface_) and via GUI (_Graphical User Interface_), in addition to testing one of them (the git clone) via CLI (_Command Line Interface_).

I hope you're as eager to get started as I am to guide you along the way! 🧑‍🏫

Go to [lesson 0](./0.md) to _setup_ the local environment with Docker.
