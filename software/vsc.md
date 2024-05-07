---
title: VS Code
layout: page
parent: Software
nav_order: 2
---

# Visual Studio Code (VSC)

_Note: you are not required to use VS Code for your CIE42X0-PD assignments. However, it is extremely useful, and trust me---if you ever plan on doing anything related to programming again in your life after this quarter (for example, a thesis...), it is worth the effort to learn this tool._ 

Visual Studio Code (VSC) is and _Integrated Development Environment_ (IDE): a software that helps users program more effectively, as it combines different workflows in one place. For our purpose VS Code is very useful because allows us to:
- manage files and sub-directories within our working directory
- execute Python code (and any other programming language!), including Jupyter notebooks
- manage Python environments
- use Git and version control
- many other things, especially with Extensions!

Although Jupyter Lab and Jupyter Notebook are also IDE's, they don't provide as many features as VS Code. The availability of extensions, in particular, is exceptional. 

_The remainder of this page covers installation and use of VS Code. Please contact Robert directly if you have any questions or suggestion for improvement, as this is the first time using these instructions with students._

## Installation

The primary steps are:
- download the installer from [code.visualstudio.com/download](https://code.visualstudio.com/download){:target="_blank"}
- get familiar with the interface
- install a few useful Extensions
- sign in to your GitHub account
- use it!

### Extensions

_More info coming soon!_

Select the "Extensions" box on the left side of the application (the symbol is four boxes), then search for and install the following (entering the ID in the search box turns up the right result):
- Python (Extension ID: `ms-python.python`)
- Jupyter (Extension ID: `ms-toolsai.jupyter`)
- GitHub Pull Requests (Extension ID: `GitHub.vscode-pull-request-github`)

### Using Git and Version Control

We will use the HTTPS protocol for cloning repositories, since VS Code allows you to authenticate yourself by logging in to your GitHub account via the application (this avoids setting up SSH).

It is very easy to clone a repository and start working on a project:
- Copy the HTTPS clone link from the repository on github.com
- Open a new window (File >>> New Window)
- Under the "Start" menu, select "Clone Git Repository"
- Paste the link, then choose the location where you would like to store the repository (hint: in your `.../HOS/` directory!)

You should have already installed the extension GitHub Pull Requests, which will allow you to log in to GitHub. After this you will be able to push back to the remote repository (github.com) using the "Source Control" tab on the left of the application.

_More info/screenshots coming soon!_

### Activating a Python Environment

The easiest way to do this is to install.