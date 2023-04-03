# Simple test

This is a simple test to assess technical knowledge and ability. There are no real wrong answers as this test is mainly used to assess the candidate's methodology and thinking. You are allowed to use any resources you want to complete the test (documentation, chatGPT, stackoverflow, etc...) as long as you justify your answers.

**How to complete the test : fork this repository, complete the test and send us a pull request.**

## Test

### 1. Create a simple backend application

- create a simple backend HTTP application listening on port 8080. The application should be written in language of your choice
- the application must have a single endpoint `/hello` that returns a JSON object with a `message` field containing the string `Hello World!` and with HTTP status code 200

### 2. Choose one solution to deploy the application

Choose one hosting solutions (GKE, VM, Cloud Run, Cloud Functions, ...) accross Google Cloud Platform services and explain why you chose it.

### 3. Package the application in a Docker container

- create a Dockerfile that builds the application and packages it in a container
- use a multi-stage build to keep the container size as small as possible
- the container should be based on a Linux distribution of your choice
- the container should run as a non-root user

### 4. Deploy the application

Manually deploy the application using the solution you chose in the previous step.

### 5. Create a small documentation for the application

Create a small documentation for the application. The documentation should explain how to easily build and deploy the application.

### 6. Add observability to the application

- explain what observability is and how you would add observability to the application
- explain what would be the most important metrics to monitor and why

### 7. Create a Github workflow to build and deploy the application

Create a Github workflow that builds the application and deploy it to the hosting solution you chose in the previous steps.
