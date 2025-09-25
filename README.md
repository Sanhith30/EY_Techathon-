# EY_Techathon-
Each member clones the repository to their own machine using:

text
git clone <repo_url>
Create a New Branch

Every team member creates a feature branch (e.g., feature-ui, feature-backend, feature-ml, feature-docs):

text
git checkout -b <branch_name>
Work on Assigned Tasks

Code on your own branch. Add and commit changes frequently:

text
git add .
git commit -m "Describe your changes"
Push Changes to GitHub

Push your branch to the remote repository:

text
git push origin <branch_name>
Pull Requests & Code Review

On GitHub, open a Pull Request (PR) from your branch to the main branch. Team members review and comment on each other’s code before approving.

Merge After Review

Once reviewed, merge the PR to main. Only one person merges at a time to avoid conflicts.

Sync Regularly

Before starting new work, pull the latest main branch to your local repo and update your feature branch:

text
git checkout main
git pull origin main
git checkout <branch_name>
git merge main
Repeat Steps 4-8

Continue updating, pushing, reviewing, and merging until the project is complete.
