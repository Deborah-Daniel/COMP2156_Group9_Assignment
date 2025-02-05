# COMP2156_GroupX_Assignment

## Group Members
- *Leader:* Deborah Daniel (101438707) - https://github.com/Deborah-Daniel/comp2156.git
- *Member 2:* Harsh wardhan Singh (101503035) - https://github.com/iharsh8055/comp2156.git
- *Member 3:* Gunel Nasibova (101516253) - https://github.com/guneln/comp2156.git
- *Member 4:* Gurwinder Singh (101473101) - https://github.com/Gurwinder24055
- *Member 5:* Jagjeet Kaur (101471675) - https://github.com/jagjeet524/comp2156.git
- *Member 6:* Khushpreet Kaur (101471893) - https://github.com/Khushpreet05

## Project Description
This repository contains collaborative work for the COMP 2156 DevOps assignment.

1. Collaborative Git workflows: Using Git for version control, branching, merging, and handling collaboration between multiple team members.
2. Branching strategies: Following best practices for organizing code using Git branches (e.g., main, feature, hotfix, develop).
3. Continuous Integration/Continuous Delivery (CI/CD): Setting up automated pipelines to run unit tests, build, and deploy code using Travis CI or GitHub Actions. This aims to ensure code quality, automate the testing process, and make the deployment process faster and more reliable.
4. Infrastructure as Code (IaC): Using tools like Terraform or Ansible for automating infrastructure provisioning and configuration management.


## Setup Instructions
- Create and set up the GitHub repository.
- Add collaborators to the repository.
- Clone the repository to your local machine for access and uploads.
- Create a separate branch for each team member.
- Set up a GitHub Actions workflow for automation.
- Commit changes with clear messages for better file tracking.
- Merge branches while resolving any conflicts.
- Push changes to both individual branches and the main branch.


## CI/CD Pipeline
Continuous Integration (CI):
- The CI pipeline is started each time a member submits a Pull Request (PR) to the 'main' branch 
 or pushes code to their branch.
 
- The pipeline uses automated tests to make sure the modifications to the code don't interfere with already-existing functionality.This covers any important tests defined by the project as well as unit and integration tests.

- The code is considered safe to merge into the `main` branch if the tests are successful.
  
 Continuous Deployment (CD):
- When a Pull Request is merged into the main branch, the CD pipeline is activated.
- The application is built and deployed to the specified environment (such as production or staging) automatically by the pipeline.
- To update the team on the deployment status, notifications are delivered to them via email or messaging apps (like Slack).


## Branching Strategy
A branching strategy describes the steps involved in creating, maintaining, and merging branches within a Git repository. Each team member will work on their own branch as part of the project's feature branching architecture. Pull Requests (PRs) are used to integrate branches into the main branch in order to guarantee harmonic collaboration. Each team member must clone the repository, establish a branch using their Student ID and Name format, push the branch to GitHub, make modifications and commit, periodically sync with the main branch, and merge the branch into the main branch in order to create and switch to an individual branch. This method ensures individual workflows, permits code review, minimizes conflicts, and maintains a clean history.
- Every team member uses their student ID and name to create a branch. For instance, 101471893-Khushpreet.
- Work is done on each branch separately. Changes are made by each member to their specific branch.
- Pull Requests (PRs) are used to integrate branches into the main branch.
- Before merging, pull requests are reviewed to make sure the changes are correct and follow to project standards.
- To prevent conflicts, pull from the main branch to update your branch on a regular basis. For instance, git pull origin main.
- To keep it current and share changes with others, push your branch to the remote repository.
- Before merging, solve any merge arguments in the Pull Request.
