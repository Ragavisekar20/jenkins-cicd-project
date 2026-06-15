# Jenkins CI/CD mini Project
## Project Overview

This project demonstrates a simple CI/CD pipeline using Github, Jenkin, Docker and Linux.

whenever code is pushed to Github:
-Jenkins automatically pulls the latest code
- Build a Docker image
- Deploy the application inside a Docker container
- Application becomes accessible in browser

## Tools used
-Git 
-Github
-Jenkins
-Linux
-Nginx

## Pipeline Stages
1. Clone
2. Build Docker Image
3. Deploy Container

## Project Architecture

Developer
    |
Github Repository
    |
Jenkins Pipeline
    |
Docker Build
    |
Docker Container Deployment
    |
Browser Output

## Jenkins Pipeline
-Clone source code from Github
-Build Docker image using Dockerfile
-Deploy container on port 8081

## Output
Application successfully deployed in browser

Browser URL:
http://localhost:8081

Output:
Hello Devops Engineer!
Jenkins CI/CD pipeine working successfuly


## Result
Successfully created Jenkins CI/CD pipeline integrated with Github.

<img width="1282" height="718" alt="Github Repository" src="https://github.com/user-attachments/assets/681ec353-70a2-4afc-89cc-18ea8f85de9c" />
<img width="1286" height="689" alt="Browser output" src="https://github.com/user-attachments/assets/39b545b0-1e36-4ff7-a350-6e40e7c498c9" />
<img width="645" height="380" alt="Docker container output" src="https://github.com/user-attachments/assets/cfd7568a-cbe6-44e1-bdb2-9156191f7b88" />
<img width="1288" height="613" alt="Jenkin" src="https://github.com/user-attachments/assets/f9764d24-61bb-47a7-aa45-a3613391e717" />
<img width="1288" height="613" alt="Jenkins Build Success" src="https://github.com/user-attachments/assets/1255a2a7-0958-4e6f-901f-6f24a09d3b76" />
<img width="1284" height="619" alt="Full Pipeline Flow" src="https://github.com/user-attachments/assets/9ed93f5e-a2c7-4610-8bf3-d57b3cc45d8e" />




