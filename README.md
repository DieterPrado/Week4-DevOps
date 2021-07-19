# DevOps
### Table of contents
- General info
- Technologies
- Setup
- Things learned:
- Continuos integration
- Continuos delivery
- Deployment types
- Incident Response
- Site realiability


------------

### General info
This course taught about devops. It taught the concepts of continouos delivery and continuos integration and how to use certain technologies like jenkins (to automate) and docker to propperly test and prepare changes or updates for production. It also taught different deployment types like canary deployment or rolling deployment. Differente deployment strategies can be used depending our needs. 


------------

### Technologies
- Jenkins
- Docker



------------

### Setup

###### Jenkins
- Go to https://www.jenkins.io/
- Download jenkins
- Complete installation process

###### Docker
- Go to https://www.docker.com/products/docker-desktop
- Donwload docker
- Complete installation process




------------
### Things learned
- Continuos Integration is. Workflow in which each developer adds small changes to the main branch after those changes pass automatic tests.
- Continuos Delivery is. CI extension where even the deployment is automated. 
- Code coverage: How much of the code is tested. Doesn't mean the code is correctly tested, so we need to be careful.
- **Deployment types: **
***Blue/Green deployments:*** At any given time, only one server is handling requests.
***Canary deployments:*** Apply changes to only a certain percentage of users or servers. This way we don't compromise our all server in case the changes are bad.
***Rolling deployments:*** Deployment strategy that slowly replaces previous versions of an application with new versions of an application by completely replacing the infrastructure on which the application is running.
- Incident response: Verify the size of the problem. Always notify your clients about the issues you're having, usually by an status page. After solving the problem write a "postmortem", this will help the company and you. This will also inspire trust in the client about you.
- Site realiability: How companies measure the quality of their products. 
- SLO - Service Level Objectives: Its the metric, for exmaple, that our latency is less than 50 ms in a space of 5 minutes all month.
- SLI - Serivece Level Indicators: The amount of errors, latency, time to send an email, time to answer a specific path in our API
- Always have homogenity between all the project process (devolopment, testing, production)
- Always use versions you have already used and tested.



