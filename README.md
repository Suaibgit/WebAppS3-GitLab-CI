# Building a CI/CD pipeline for a simple React App and Deploy to AWS S3

## Description

The project files have been forked from public GitLab repo, except the pipeline file .gitlab-ci.yml. This project is all about this file. In this file contains a script that will build the project, test the project and deploy it to AWS S3.

## Features

- Continuous Deployment and Continuous Delivery concept is implemented by introducing staging approach where two S3 bucket is used to test deployment to check any error on final Delivery.
- Main branch is protected. Committing from any other branch will not deploy the App to AWS.
- All other branches have permission only to build and test the app.
- After an approval of a merge request from any feature branch will allow deploying the app to AWS.
