# detection-as-code-pipeline
Detection-as-Code pipeline using Sigma rules, GitHub Actions, and automated validation workflows for security detection engineering.
## Overview
This project demonstrates Detection-as-Code principles by managing Sigma detection rules through Git-based workflows and automated validation using GitHub Actions. Detections are stored in version control, tested with sample event data, and automatically validated whenever changes are pushed to the repository. The workflow automatically executes whenever code is pushed to the repository, validating detection content before future deployment stages.
## Technologies

- Sigma Rules
- Git
- GitHub
- GitHub Actions
- YAML
- JSON
## Detection Workflow

1. Create or modify Sigma detection rules.
2. Commit changes to Git.
3. Push updates to GitHub.
4. GitHub Actions automatically validates detection files.
5. Detection changes can be reviewed before deployment.

## Project Screenshots
### Repository Structure

<img width="975" height="140" alt="image" src="https://github.com/user-attachments/assets/907f0e47-b66e-4910-965b-f7e546aa147e" />

The Detection-as-Code repository stores Sigma detection rules, GitHub Actions workflow configurations, and project documentation in a version-controlled environment.

<img width="707" height="315" alt="image" src="https://github.com/user-attachments/assets/6c52755b-6a65-4912-8d90-631673426bfd" />
Sigma detection rules and test event data stored in a version-controlled repository to support automated validation workflows.

### Automated Validation Pipeline
 <img width="830" height="740" alt="image" src="https://github.com/user-attachments/assets/9c5cb8d0-96b5-42df-bd5c-1ed4a59444d8" />
 
GitHub Actions automatically executes validation workflows whenever detection content is pushed to the repository. Workflow execution status is visible directly from the Actions dashboard.

### Workflow Execution Results

<img width="841" height="108" alt="image" src="https://github.com/user-attachments/assets/04e96409-b8bf-4f6b-9325-79fda772535b" />

Successful workflow execution validates repository content and confirms the presence of detection rule files before future deployment stages.


## Skills Demonstrated

- Detection Engineering
- Detection-as-Code
- CI/CD Pipelines
- Git Version Control
- GitHub Actions
- Security Automation
- Change Management

## Sample Detections

- Suspicious Login
- Multiple Failed Login Attempts
- Suspicious PowerShell Execution

## Test Data

- malicious.json (failed login event)
- benign.json (successful login event)
