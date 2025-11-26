DevOps FAT2 – Assignment

This assignment demonstrates my understanding of Linux commands, Docker, Git/GitHub workflow, and basic DevOps concepts. I created a Dockerfile, built a Docker image, and pushed the project to GitHub.

1. Five DevOps Concepts

Continuous Integration (CI)

Automatically merging and testing code changes in a shared repository.

Ensures that new code integrates well with the existing codebase.

Continuous Deployment (CD)

Automatically releasing every successful code change to production.

Reduces manual deployment errors and accelerates delivery.

Infrastructure as Code (IaC)

Managing and provisioning infrastructure using code instead of manual steps.

Makes infrastructure consistent, repeatable, and version-controlled.

Containerization

Running applications inside lightweight, isolated containers.

Ensures the application works the same across different environments.

Version Control

Tracking and managing code changes using tools like Git.

Enables collaboration, rollback, and history tracking of changes.

2. How I Completed This Assignment
Steps Followed

Create Project Folder

Created a folder named docker-linux-basic.

Create Dockerfile

Created a Dockerfile containing basic Linux commands:
FROM ubuntu:latest
RUN apt-get update
CMD ["bash"]

3.Build Docker Image
docker build -t linux-basic-image .
docker run -it linux-basic-image

4.Initialize Git and Push to GitHub
git init
git add .
git commit -m "Initial commit with Dockerfile and README"
git branch -M main
git remote add origin https://github.com/eshaanivdekar/docker-linux-basic.git
git push -u origin main

5.Push Image to Docker Hub (Public)
docker login
docker tag linux-basic-image eshaanivdekar/linux-basic-image:latest
docker push eshaanivdekar/linux-basic-image:latest

4. What I Learned

Practical Docker skills: writing Dockerfiles, understanding image layers, container isolation.

Git/GitHub workflow: commits, branches, remote repositories, version control.

DevOps concepts in action: CI/CD ideas, containerization, automation.

Linux command usage inside containers.

5. Conclusion

This assignment helped me understand a complete DevOps flow:

Write code → Containerize with Docker → Version control using Git → Publish on GitHub → Share Docker image publicly.

It strengthened my practical knowledge of Linux, Docker, Git, and DevOps practices, which are essential skills for any DevOps engineer.
