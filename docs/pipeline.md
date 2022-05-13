# Pipeline

The pipeline is triggered when a new push happens in the specific branch in case of this project is "Main" branch

### 1. The pipeline uses something called orbs to install required software/dependencies

- node: circleci/node@5.0.2
- aws-cli: circleci/aws-cli@1.3.1
- eb: circleci/aws-elastic-beanstalk@2.0.0

### 2. The pipeline install the required dependencies for backend and frontend

### 3. The pipeline build frontend and backend of the application

### 4. The pipeline deploy the frontend and backend of the application


![diagram](/docs/screenshots/pipeline.png)