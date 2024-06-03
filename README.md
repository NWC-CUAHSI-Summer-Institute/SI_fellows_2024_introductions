# Summer Institute 2024 - GitHub Training

Welcome to the National Water Center Innovators Program Summer Institute GitHub training repository! This repository is designed to help participants of the Summer Institute get comfortable with using GitHub, a tool for collaborative software development and data science.

## Training Objective

The goal of this training is to familiarize you with the basics of GitHub. You will learn how to clone a repository, make edits, and commit changes. This exercise is intended to prepare you for contributing to collaborative projects during the Summer Institute, ensuring that all code and findings are public and reproducible.
Getting Started

## Prerequisites
We will be using the CIROH 2i2c cloud compute platform during the Summer Institute bootcamp. You can access that platform here: https://ciroh.awi.2i2c.cloud/. Please start up a "small" compute instance. It might take a minute or two to start up. When it starts, it will open up a bash terminal on the right, and a file explorer on the left.

# Exercise Instructions

By now you should have a GitHub Account with two factor authentification and access to the 2i2c cloud compute platform. 

You are interfacing with a Linux virtual machine. You'll need to follow these steps to add your information to the `introductions.txt` file. Now there will be a file called ".gitconfig", notice that hidden files have a "." in front of them.



- Clone the Repository: `git clone https://github.com/NWC-CUAHSI-Summer-Institute/training_git_introductions_2024.git`
- Navigate into the cloned repository directory: `cd summer-institute-2024`
- Configure your github information:
On the top of the virtual compute interface there are some dropdown items. Click on "View" and toggle on "Show hidden files".
In the directory called ".git", which will be shown in grey as a hidden folder, there is a file called "config (".git/config"). Open that file, and add the following information to the bottom of the file.
```
[user]
	email = youremailassociatedwithgithub@university.edu
	name = yourgithubusername
```
- Edit the Introduction File
    Open the file introductions.txt in a text editor of your choice.
    Add your name, your university, and two or three sentences describing your research interests.
- Commit Your Changes
After editing the file, save your changes and return to your terminal.
Use the following commands to commit your changes to the repository:
```
git add introductions.txt
    git commit -m "Add my introduction"
    git push
```
- Make a pull request