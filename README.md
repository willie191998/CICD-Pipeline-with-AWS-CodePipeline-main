# Deploying a Static Web Application with CI/CD on AWS 🚀

This project is a CI/CD pipeline for a static web application that offers city-to-city directions.

## AWS Services Utilized 📦

- 🔸 **AWS CodePipeline**
- 🔸 **AWS CodeCommit**
- 🔸 **AWS CodeBuild**
- 🔸 **AWS CodeDeploy**
- 🔸 **Amazon S3**
- 🔸 **Amazon EC2**


## Architecture Diagram

![Architecture Diagram](https://github.com/Dom7k/CICD-Pipeline-with-AWS-CodePipeline/blob/main/architecture%20diagram.gif)

## Deployment Process 🪂

1. **Version Control Setup:**
   - Push source files to AWS CodeCommit, setting up a repository for version control.

2. **Build Automation:**
   - Configure AWS CodeBuild with build scripts to automate the build process whenever changes are pushed to the repository and save the build artifacts to an S3 bucket.

3. **Deployment Automation:**
   - Create deployment scripts and configure AWS CodeDeploy to automate the deployment process to an EC2 instance.

4. **Pipeline Automation:**
   - Set up AWS CodePipeline to integrate the version control, build, and deployment processes, creating a seamless CI/CD pipeline.

## Key Learnings ✨

- Implementing the CI/CD pipeline with AWS CodePipeline streamlines the build and deployment process, enhancing efficiency and reducing operational overhead.

## How to Clone This Project

To clone this project, follow these steps:

1. Open your terminal or command prompt.
2. Run the following command to clone the repository:

   ```bash
   git clone https://github.com/Dom7k/CICD-Pipeline-with-AWS-CodePipeline.git
   cd CICD-Pipeline-with-AWS-CodePipeline

