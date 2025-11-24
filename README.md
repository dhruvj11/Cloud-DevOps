# DevOps-FAT2

Git Repository for DevOps FAT2

## 5 DevOps Concepts

### Version Control Systems

- Helps maintain a full history of code changes.
- Supports teamwork through branching, merging, and pull requests.
- Makes it easy to revert mistakes and track contributions (example: Git).

### Containerization

- Packages applications and dependencies into portable units called containers.
- Ensures consistent behavior across development, testing, and production environments.
- Example: Docker.

### CI (Continuous Integration)

- Developers frequently merge code into a shared repository.
- Automated builds and tests detect issues early.
- Improves code quality and reduces integration conflicts.

### CD (Continuous Deployment/Delivery)

- Automates the deployment of applications after successful testing.
- Enables quick and frequent releases with minimal manual intervention.
- Reduces deployment risks and increases release confidence.

### IaC (Infrastructure as Code)

- Infrastructure is defined and managed using configuration files or scripts.
- Ensures repeatability, versioning, and automation of environments.
- Tools like Terraform or CloudFormation eliminate manual provisioning.

## How was this assignment completed?

- Created a repository on GitHub and cloned it
- Created a Dockerfile with basic linux commands.
- Built the Dockerfile using docker build -t dhruvjadhav012/fat2 .
- Ran it with docker run dhruvjadhav012/fat2 to verify everything works
- Pushed it to DockerHub using docker push dhruvjadhav012/fat2
- [DockerHub link](https://hub.docker.com/r/dhruvjadhav012/fat2) 

- Pushed Dockerfile to GitHub using:
    - `git add .`
    - `git commit -m "Dockerfile with basic linux commands added"`
    - `git push`
- Added 5 DevOps concepts to README.md and pushed the changes to github

## How this project helped me learn DevOps, Linux, Git, and Docker?

- I learned basic Linux commands and how they behave inside a container.
- Understood how Dockerfiles are structured and how images are built.
- Practiced essential Git operations such as committing, pushing, and maintaining a repository.
- This assignment gave me exposure to all the core DevOps concepts.
- Learned how different DevOps tools work together in a real workflow.