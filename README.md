# Single Docker Container Deployment to AWS Elastic Beanstalk With GitHub Actions
## Prerequisites
1) Create a new Elastic Beanstalk application and environment manually with the following configuration:

* Name: docker_single_container_deployment
* Platform: Docker
* Platform Branch: Docker running on 64bit Amazon Linux 2
* Application code: Sample application (default choice)

2) Create an IAM user with programmatic access and the following permissions: AWSElasticBeanstalkWebTier, AWSElasticBeanstalkManagedUpdatesCustomerRolePolicy, and AmazonS3FullAccess

3) Create 2 repository secrets in your GitHub repository: AWS_ACCESS_KEY and AWS_SECRET_KEY of the IAM user newly created

## Overview
