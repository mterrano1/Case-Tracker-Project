# Case-Tracker-Project


## See it here

https://www.youtube.com/watch?v=cONFD37A6y8


## Description

This is a case tracker application that allows customers to file a complaint. The complaint is automatically assigned to the manager with the fewest cases assigned to them. That manager can then assign the case to a researcher who can disposition the case once they're done researching it. The manager can view details about all of the cases that have been filed by accessing their dashboard page.

The application is built using a React frontend, Flask API, Rails API, and two PostgreSQL databases for each API. All of these components are wrapped in Docker containers and deployed to AWS EKS. Volume mounts are used to persist data from the PostgreSQL databases to AWS EBS. Terraform is used to create most of the AWS resources and create the Kubernetes cluster on EKS.


## Submodules

Client - https://github.com/mterrano1/case-tracker-client

Flask - https://github.com/mterrano1/case-tracker-flask

Rails - https://github.com/mterrano1/case-tracker-backend

Docker - https://github.com/mterrano1/case-tracker-docker
