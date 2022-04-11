# Serverlss.com Harness CD Next Gen Deployment Lab

## Introduction

This lab will take you through how Harness can do serverless.com deployments in CD Next Gen. Harness will be able to deploy the serverless functions via the serverless.com framework, verify that the function was deployed successfully, and that the function is tracked and visibile in the service dashboard. 

## Pre-Requisistes for the Lab

- serverless.com YAML 
- AWS Credentials to deploy lambda 
- Harness Account
- Github Account 

## Lab

1. Create a Project

2. Create a Pipeline

3. Add a CD Stage

4. Configure a Service

5. Add a Serverless Manifest

6. Add an Artifact for Harness to manage

7. Configure an Environment

8. Configure an AWS Infrastructure Definition

9. Add a Serverless Deploy Step to the Execution Section 

10. Run Pipeline

---

*Credit* 
Serverless.com Team provides sample apps, we are building off one of these for our example - https://github.com/serverless/examples/tree/v3/aws-node-rest-api 