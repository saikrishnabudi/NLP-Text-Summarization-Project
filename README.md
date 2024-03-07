# NLP-Text-Summarization-Project

End To End NLP Text Summarization Project

Project Overview:The project is about building a text summarization tool from scratch. Text summarization is the process of condensing a piece of text to its main points or key information.

Workflow:

1. Update Configuration Files: These files contain settings and parameters used throughout the project.
   
   - config.yaml: Contains general configuration settings.
     
   - params.yaml: Stores parameters used for the summarization model.
     
2. Update Entities: This likely refers to updating any specific entities or objects used in the project, such as data structures or classes.
   
3. Update Configuration Manager: This component manages the configuration settings of the project.
   
4. Update Components: Refers to updating various parts or components of the project, such as the summarization algorithm or data preprocessing steps.
   
5. Update Pipeline: The pipeline is the sequence of steps involved in the summarization process. This step involves updating it to incorporate any changes made.
    
6. Update Main.py: The main Python script that orchestrates the execution of the project.
    
7. Update App.py: This file likely contains code related to deploying the summarization tool as a web application.

How to Run:

To run the project on your local machine, follow these steps:

1. Clone the Repository: Download a copy of the project from the GitHub repository.
   
2. Create Conda Environment: Set up a virtual environment for the project using Conda.
   
3. Install Requirements: Install the necessary Python packages listed in the requirements.txt file.
   
4. Run the Application: Execute the app.py file using Python.

Deployment on AWS:

The project also includes instructions for deploying the summarization tool on AWS using services like EC2 (Elastic Compute Cloud) and ECR (Elastic Container Registry).

1. Build Docker Image: Create a containerized version of the project using Docker.
   
2. Push Image to ECR: Store the Docker image in the AWS Elastic Container Registry.
   
3. Launch EC2 Instance: Set up a virtual machine on AWS using EC2.
   
4. Pull Image from ECR: Retrieve the Docker image from the Elastic Container Registry.
   
5. Run Docker Image on EC2: Deploy the Docker image on the EC2 instance.

Policy and Setup:

- These steps involve configuring access permissions and setting up resources on AWS, such as IAM users, EC2 instances, and ECR repositories.
  
- Policies ensure that the necessary permissions are granted for actions like accessing EC2 and ECR.
  
- GitHub secrets are used to securely store sensitive information like AWS access keys.

In summary, this project involves building a text summarization tool, setting up a development environment, and deploying it on AWS for wider use. The steps provided guide through the process from development to deployment, ensuring smooth execution at each stage.
