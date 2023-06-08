# cloud-server

## Overview

This lab focuses on deploying a Node.js server to AWS EC2 using Elastic Beanstalk. You will have the option to choose a server you've built previously, either a simple API or web server or a socket.io event hub. The server should not require a database. You will check in your server to GitHub and perform two tasks to deploy it using Elastic Beanstalk.

## Resources

## Feature Tasks

Deploy a simple Node.js server to EC2 using Elastic Beanstalk.

Choose a server you've built previously:
Option 1: A simple API or Web Server
Option 2: A socket.io event Hub
The server should not require a database.
Check in your server to GitHub.
Task 1:

Create a new environment using Elastic Beanstalk from the AWS Control Panel (GUI).
Manually deploy your application to this environment by uploading a .zip file.
Task 2:

Using the same server, create a new environment using Elastic Beanstalk from your terminal.
Manually deploy your application to this environment by using eb deploy.
Documentation
In your README.md, include the following:

## Deployment Process

Document the processes you followed to deploy your Node.js server to AWS EC2 using Elastic Beanstalk. Include step-by-step instructions or commands for each task.

Task 1: Deploying through GUI
Sign in to the AWS Control Panel.
Navigate to Elastic Beanstalk.
Create a new environment.
Select the appropriate platform and configuration.
Upload the .zip file containing your server code.
Configure environment settings.
Review and launch the environment.
Wait for the deployment to complete.
Access the deployed server using the provided link.
Task 2: Deploying through CLI
Open your terminal.
Install the Elastic Beanstalk CLI if not already installed.
Navigate to your server's project directory.
Create a new environment using Elastic Beanstalk.
Set the appropriate platform and configuration.
Run the command eb deploy to deploy your application.
Monitor the deployment progress.
Access the deployed server using the provided link.

## Links

- http://cloud-server-dev222.us-east-2.elasticbeanstalk.com/

- http://lab-16-env.eba-m8miwstx.us-east-2.elasticbeanstalk.com/

## Collabs

- Ryan helped me during code review
