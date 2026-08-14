# DevOps Week 02

## Project Overview

This project was created as part of my DevOps Week 02 hands-on activity.


The project demonstrates a practical Git and GitHub workflow used in a DevOps environment. It covers repository management, branching, commits, merging, Pull Requests, merge conflict resolution, and project documentation.


## Objectives

The main objectives of this project are to:

- Practice Git version control
- Create and manage feature branches
- Make and track changes using commits
- Merge feature branches into the main branch
- Work with GitHub Pull Requests
- Practice resolving merge conflicts
- Document a project using README.md

## Technologies

- Git
- GitHub
- Python
- Docker
- YAML

## Project Structure


DevOps-Week-02/
├── App.py
├── Dockerfile
├── README.md
├── config.yaml
├── requirement.txt
└── .gitignore


| File               | Description                                          |
| ------------------ | ------------------------------------------------------ |
| `App.py`           | Main Python application                               |
| `Dockerfile`       | Instructions for building the application container   |
| `config.yaml`      | Application configuration                             |
| `requirement.txt`  | Python dependency file                                |
| `.gitignore`       | Files and directories excluded from Git                |
| `README.md`        | Project documentation                                  |

## Git Workflow

The project follows this general workflow:


Create Repository
       ↓
Create Feature Branch
       ↓
Make Changes
       ↓
Commit Changes
       ↓
Push Branch
       ↓
Create Pull Request
       ↓
Code Review
       ↓
Merge into Main


## Docker

The application can be built using the included Dockerfile:


docker build -t devops-week-02 .


Run the container with:


docker run devops-week-02


## Git Branches

The project uses feature branches to separate development work from the main branch.

Branches used during this activity include:

- `feature/application`
- `feature/docker`
- `feature/documentation`
- `main`

## Learning Outcomes

Through this activity, I practiced:

- Git repository initialization
- Git branching
- Git commits
- Git merging
- GitHub repository management
- Pull Requests
- Merge conflict resolution
- Project documentation

## Author

Light Osita
