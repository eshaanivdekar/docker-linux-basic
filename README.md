# &nbsp;DevOps FAT2 – Assignment



This repository contains my DevOps FAT2 assignment, where I demonstrated my understanding of Linux Commands, Docker, and Git/GitHub workflow by creating a Dockerfile, building a Docker image, and pushing the project to GitHub.



#### &nbsp;1. Five DevOps Concepts



###### 1\. Continuous Integration (CI)

&nbsp;  Automatically merging and testing code changes in a shared repository.



###### 2\. Continuous Deployment (CD)  

&nbsp;  Automatically releasing every successful code change to production.



###### 3\. Infrastructure as Code (IaC)  

&nbsp;  Using code to configure and manage infrastructure instead of manual setup.

###### 

###### 4\. Containerization  

&nbsp;  Running applications inside lightweight, isolated containers to ensure consistency.



###### 5\. Version Control  

&nbsp;  Tracking and managing code changes using systems like Git.



#### 2\. Steps I Followed to Complete the Assignment



###### Step 1 – Create Project Folder

&nbsp;

I created a folder named: `devops`



###### Step 2 – Created Dockerfile

&nbsp; 

I wrote a Dockerfile containing Linux commands such as:  





###### Step 3 – Install \& Fix Docker Desktop

&nbsp;

\- Installed Docker Desktop on Windows  

\- Fixed WSL update issue  

\- Updated WSL using: `wsl --update`  

\- Restarted PC  

\- Started Docker Desktop successfully  



###### Step 4 – Build Docker Image 

###### I built the image using:  



```powershell

docker build -t devops-image .





###### Step 5 – Initialize Git and Push to GitHub



git init

git add .

git commit -m "first commit"

git branch -M main

git remote add origin git remote add origin https://github.com/eshaanivdekar/docker-linux-basic.git



#### &nbsp;3. What I Learned from This Assignment

###### 

###### &nbsp;Docker Concepts

###### 

How to write a Dockerfile



How images are built in layers



How containers are isolated and consistent



&nbsp;Git \& GitHub



Initializing a repository



Committing changes



Working with branches



Pushing to GitHub



&nbsp;DevOps Concepts

This activity taught me real DevOps practices:



Automation



Version control



Consistency



Collaboration



Using tools like Git and Docker



#### &nbsp;Conclusion



This assignment helped me understand a complete DevOps flow: Write code → Containerize with Docker → Version control using Git → Publish on GitHub.

