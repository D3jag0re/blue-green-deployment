# Blue-Green-Deployment

This is based off the DevOps Roadmap Project [Blue Green Deployment](https://roadmap.sh/projects/blue-green-deployment)

Setup a bastion host for managing access to private infrastructure. 

This is number 20 of [DevOps Projects](https://roadmap.sh/devops/projects) as per roadmap.sh

## Description From Site 

The goal of this project is to practice setting up a blue-green deployment strategy for a simple web application. This will allow you to deploy your application in a more efficient and reliable way.

## Requirements

You are required to take an existing application (e.g. the one you built in multi-container service project) and setup a blue-green deployment strategy for it. The goal is to deploy the next version of the application in a separate container and switch the traffic to the new container only when the new version is ready.

### Bonus 

- [] Setup a CI/CD pipeline to automatically deploy the application to the server when the code is pushed to the repository.
- [] Setup a monitoring system to monitor the application and the deployment process.

After finishing this project you will have a good understanding of how to deploy a containerized application in a more efficient way without downtime and with zero data loss.

## prerequisites

- Setup the following repository secrets:
    - DO_TOKEN : Digital Ocean access token
    - DO_SPACES_SECRET_KEY : Digital Ocean spaces secret key (for Terraform state file)
    - DO_SPACES_ACCESS_KEY : Digital Ocean spaces access key (for Terraform state file)
    - DO_SSH_PUBLIC_KEY_PRIVATE : Keypair to be used for Private VM 
    - DO_SSH_PRIVATE_KEY_PRIVATE : Keypair to be used for Private VM

## To Run  

- Run workflow 


## Notes 

- Notes
## Lessons Learned

- Lessons