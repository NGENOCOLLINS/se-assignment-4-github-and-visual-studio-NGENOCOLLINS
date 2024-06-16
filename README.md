
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.


Questions:
#Introduction to GitHub:

What is GitHub, and what are its primary functions and features?

GitHub is a web-based platform using Git for version control, facilitating collaborative software development. Key features include repositories, branches, pull requests, issues, project management tools, wikis, GitHub Actions for automation, and various collaboration tools.

# references
https://guides.github.com/introduction/flow/
#Repositories on GitHub:

A GitHub repository is a storage space for project files and their revision history. To create a new repository: log in, click the "+" icon, select "New repository," enter details, and optionally initialize with a README, .gitignore, and license . Essential elements include a README.md, LICENSE, .gitignore, source code folder, docs folder, and tests 
# references
https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository

#Version Control with Git:
Version control manages code changes over time. Git is a distributed version control system allowing multiple developers to work simultaneously. GitHub enhances this with a central repository, pull requests, branch protection, collaboration tools, and CI/CD integration .

# references
https://opensource.com/article/18/1/step-step-guide-github

#Branching and Merging in GitHub:

Branches represent independent lines of development. They allow for feature development without affecting the main codebase. Create a branch, make changes, and merge it back using pull requests. This involves creating a branch, making changes, opening a pull request, reviewing, and merging .

# references
https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control

#Pull Requests and Code Reviews:

A pull request proposes changes to a repository, facilitating code reviews and discussions. To create: push changes, open a pull request, describe changes, and submit. To review: team members review, discuss, request changes, and approve for merging .
# REFERENCES
https://docs.github.com/en/get-started/using-git/about-git

#GitHub Actions:
GitHub Actions is a CI/CD platform automating workflows.This workflow runs on push or pull request, checking out code, setting up Node.js, installing dependencies, and running tests 
example...
name: CI Pipeline
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - name: Checkout code
      uses: actions/checkout@v2
    - name: Set up Node.js
      uses: actions/setup-node@v2
      with:
        node-version: '14'
    - name: Install dependencies
      run: npm install
    - name: Run tests
      run: npm test

# REFERENCES
https://guides.github.com/introduction/flow/

#Introduction to Visual Studio:

Visual Studio is a comprehensive IDE from Microsoft with features like IntelliSense, debugging tools, and built-in tools for database management and version control. Visual Studio Code (VS Code) is a lightweight, extensible code editor with built-in Git support and integrated terminal, suitable for various development tasks .

# REFERENCES
https://www.atlassian.com/git/tutorials/using-branches

#Integrating GitHub with Visual Studio:

Steps:

Install Git.
Open Visual Studio.
Clone repository from "Team Explorer" by entering the GitHub URL.
Sign in to GitHub.
Manage branches, commit, and push changes directly.

# REFERENCES
https://visualstudio.microsoft.com/vs/features/

#Debugging in Visual Studio:
Visual Studio offers powerful debugging tools like breakpoints, watches, call stacks, and profiling. Developers can set breakpoints to pause execution, inspect variables, and analyze call stacks to identify and fix issues in their code .

# REFERENCES
https://docs.microsoft.com/en-us/visualstudio/version-control/git-with-visual-studio

#Collaborative Development using GitHub and Visual Studio:

GitHub and Visual Studio together streamline version control, code reviews, and CI/CD processes, supporting collaborative development. For example, a team developing a web application can use GitHub for repository management, pull requests, and actions, while using Visual Studio for coding, debugging, and directly interacting with GitHub repositories .

# REFERENCES
https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests

