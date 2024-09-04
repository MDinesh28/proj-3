# Fully Automated CI/CD Pipeline with Ansible, Jenkins, and AWS CodePipeline
This project demonstrates a comprehensive CI/CD pipeline that integrates Ansible with Jenkins and AWS CodePipeline to automate the build, test, and deployment of an application across multiple environments, with a focus on Tomcat and Apache setup.

## Project Overview

  ### Automate Infrastructure Setup: 
  Using Jenkins and Ansible, the pipeline sets up Tomcat on worker nodes and configures Apache to serve the application.
  
  ### Streamline CI/CD Processes: 
  AWS CodePipeline automates the entire application lifecycle, from code integration to production deployment.  
  
  ### Parameterized Deployment: 
  The pipeline is parameterized to support dynamic deployments across dev and test environments.
  
  ### Ensure Consistency: 
  Ansible manages configurations and deployment tasks across dev, test, and prod environments, ensuring consistent results.
  
## Key Features

  ### Tomcat Setup on Worker Nodes: 
  Automated setup of Tomcat using Ansible.
  
  ### Jenkins & Ansible Integration: 
  Smooth integration for automated deployments.
  
  ### Parameterized Pipeline: 
  AWS CodePipeline is configured with parameterized values for flexibility across dev and test environments.
  
  ### Apache Integration: 
  Automated configuration of Apache web server using Ansible.
  
## How It Works

  ### Code Integration: 
  The pipeline triggers whenever a developer pushes code to the GitHub repository.
  ### Build & Test: 
  The latest code changes are automatically built and tested.
  ### Deployment: 
  Successfully tested builds are deployed to the dev, test, and prod environments using Ansible.
  
## Getting Started

  ### Prerequisites
  Jenkins installed and configured
  
  Ansible installed and configured
  
  AWS account with CodePipeline, S3, and EC2 services set up
