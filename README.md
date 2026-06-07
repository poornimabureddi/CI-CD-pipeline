# CI/CD Pipeline Automation using GitHub Actions

## Overview
A complete CI/CD pipeline using GitHub Actions to automate build, test, and deployment to AWS.

## Features
- Automated build and test on every push
- Deployment to AWS on main branch merge
- Python Flask application with unit tests
- 100% automated deployment - zero manual effort

## Tech Stack
- GitHub Actions
- Python / Flask
- pytest
- AWS

## Pipeline Stages
1. **Build** - Install dependencies
2. **Test** - Run unit tests with pytest
3. **Deploy** - Auto deploy to AWS on main branch

## How to Run Locally
```bash
pip install -r requirements.txt
python src/app.py
```

## How to Run Tests
```bash
pytest tests/ -v
```

## Author
B. Poornima | DevOps Engineer
