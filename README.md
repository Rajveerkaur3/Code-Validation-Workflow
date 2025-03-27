# CI & CD Integration with GitHub Actions  

##  Project Overview  
Using GitHub Actions, this repository demonstrates the application of Continuous Integration (CI) and Continuous Deployment (CD).  
Key features include:  
- Automatic code linting using Super-Linter.  
- A peer-review process for development work.  
- A branching strategy that separates stable code from ongoing development (main for production, dev for development).

##  Workflow Process  
1. *Super-Linter Integration*: Every commit or merge triggers the Super-Linter, automatically checking for code quality issues.  
2. *Branching Strategy*:  
   - main: Contains the super-linter.yml file. 
   - dev: Contains the README.md file for explaining the contents of the assignment.
3. *Peer Review*: All changes made in dev are reviewed by collaborators and must be approved before merging into main.  

##  Collaboration & Review Process  
- Collaborators are invited to the repository and play a key role in the pull request review process.  
- Pull requests initiate the Super-Linter check to ensure that code quality is maintained before merging.  

##  Key Milestones  
  - GitHub Actions and Super-Linter configured to run on each commit and merge.  
  - A dev branch created for ongoing development, reviewed before merging.  
  - Collaborators added to facilitate peer reviews.  
  - Pull requests created and approved as part of the review process.  
  - Changes successfully merged into the main branch after approval.  

### How to Contribute  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Rajveerkaur3/Code-Validation-Workflow.git
   cd Code-Validation-Workflow