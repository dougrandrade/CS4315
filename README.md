# Naval Postgraduate School, Data Science Certificate 2024

### This repository contains a collection of course projects in Python and R, and their associated databases and output files.

- CS 4315 Introduction to Machine Learning
	- Data Science Salary Analysis and Prediction Using KNN Regression (Jupyter Notebook)
- CS 4106 Advanced Data Analysis
	- Cell Phone Plan Cancellations Analysis and Prediction (RMarkdown pdf)


-------------------------------------------------------------------------------
## Steps for committing Jupyter Notebook .ipynb files to the GitHub repository:
### Initial Set-up:
1. Create a repo on GitHub
2. Install Git (if not already done) - https://git-scm.com/downloads
3. Clone repo by copying repo link - click on the "<> Code" button and copy the HTTPS URL
4. In Powershell, navigate to the directory you want to clone the repo
	`PS C:\Users\dougr> cd ~\Data_Science_Projects\NPS`
6. Clone the directory:
	`PS C:\Users\dougr\Data_Science_Projects\NPS> git clone https://github.com/dougrandrade/NPS_DS_Repo.git`
7. Save your Jupyter Notebook to the directory where the repo is cloned:
	`C:\Users\dougr> cd ~\Data_Science_Projects\NPS\NPS_DS_Repo`

Committing and Pushing Changes to the GitHub repo:
1. Open Powershell
2. Navigate to the repo directory: 
	`PS C:\Users\dougr> cd ~\Data_Science_Projects\NPS\NPS_DS_Repo`
3. Add changes to the staging area:
	`PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git add .`
4. Commit changes:
	`PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git commit -m "Add Jupyter Notebook"`
5. Push the changes to the repo on GitHub:
	`PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git push`
