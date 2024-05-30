# Summer Institute 2024 - GitHub Training

Welcome to the National Water Center Innovators Program Summer Institute GitHub training repository! This repository is designed to help participants of the Summer Institute get comfortable with using GitHub, a tool for collaborative software development and data science.

## Training Objective

The goal of this training is to familiarize you with the basics of GitHub. You will learn how to clone a repository, make edits, and commit changes. This exercise is intended to prepare you for contributing to collaborative projects during the Summer Institute, ensuring that all code and findings are public and reproducible.
Getting Started

## Prerequisites
We will be using the CIROH 2i2c cloud compute platform during the Summer Institute bootcamp. You can access that platform here: https://staging.ciroh.awi.2i2c.cloud/. Please start up a "small" compute instance. It might take a minute or two to start up. When it starts, it will open up a bash terminal on the right, and a file explorer on the left.

# Exercise Instructions
You are interfacing with a Linux virtual machine. You'll need to follow these steps to add your information to the `introductions.txt` file. Now there will be a file called ".gitconfig", notice that hidden files have a "." in front of them.

0. Configure your github information:
On the top of the virtual compute interface there are some dropdown items. Click on "View" and toggle on "Show hidden files". 
```
[user]
	email = youremailassociatedwithgithub@university.edu
	name = yourgithubusername
```
2. Clone the Repository: `git clone https://github.com/NWC-CUAHSI-Summer-Institute/training_git_introductions_2024.git`
3. Navigate into the cloned repository directory: `cd summer-institute-2024`

Edit the Introduction File

    Open the file summer_institute_fellows_2024_introductions.txt in a text editor of your choice.
    Add your name, your university, and two or three sentences describing your research interests.

Commit Your Changes
After editing the file, save your changes and return to your terminal.
Use the following commands to commit your changes to the repository:
    
git add summer_institute_fellows_2024_introductions.txt
    git commit -m "Add my introduction"
    git push

Verify Your Changes
Go to the GitHub repository online and check that your changes are reflected in the summer_institute_fellows_2024_introductions.txt file.
