# CS4315
## Introduction to Machine Learning and Data Mining\nNaval Postgraduate School, Data Science Certificate

This repository contains a series of Jupyter Notebook assignments, and their associated databases and output files.
There are nine assignments and one project:
- Lab 1 - Basic Python string, tuple, lists, and dictionary operations
- Lab 2 - Python functions, importing and creating text and .csv files, and text parsing
- Lab 3 - Numpy and Matplotlib operations
- Lab 4 - Pandas operations
- Lab 5 - Basic statistics operations
- Lab 6 - Text vectorization and graphical distance algorithms
- Lab 7 - K-Nearest Neighbors and imbalanced data handling
- Lab 8 - Dimensionality reduction, cluster modeling, and Gaussian mixture modeling
- Lab 9 - Naive Bayes modeling
- Final Project - Salary prediction using K-Nearest Neighbors Regression 

-------------------------------------------------------------------------------
## Steps for committing Jupyter Notebook .ipynb files to the GitHub repository:
### Initial Set-up:
1. Create a repo on GitHub
2. Install Git (if not already done) - https://git-scm.com/downloads
3. Clone repo by copying repo link - click on the "<> Code" button and copy the HTTPS URL
4. In Powershell, navigate the directory you want to clone the repo:
	  PS C:\Users\dougr> cd ~\Data_Science_Projects\NPS
5. Clone the directory:
	  PS C:\Users\dougr\Data_Science_Projects\NPS> git clone https://github.com/dougrandrade/NPS_DS_Repo.git
6. Save your Jupyter Notebook to the directory where the repo is cloned:
	  C:\Users\dougr> cd ~\Data_Science_Projects\NPS\NPS_DS_Repo

Committing and Pushing Changes to the GitHub repo:
1. Open Powershell
2. Navigate to the repo directory: 
	  PS C:\Users\dougr> cd ~\Data_Science_Projects\NPS\NPS_DS_Repo
3. Add changes to the staging area:
	  PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git add .
4. Commit changes:
	  PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git commit -m "Add Jupyter Notebook"
5. Push the changes to the repo on GitHub:
	  PS C:\Users\dougr\Data_Science_Projects\NPS\NPS_DS_Repo> git push
