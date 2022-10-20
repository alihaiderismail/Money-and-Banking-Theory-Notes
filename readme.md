# Overview

These notes cover 
Professor Saki Bigio's
221A - Monetary Economics I
course taught at 
UCLA 
during 
Fall 2022 
running from 
September 22, 2022 to December 9, 2022. 
Class meets 2:00 pm - 3:15 pm M, W. 

# Course Assignment

Students are meant to make edits to the LyX file and use Git for version control to track the changes they've made and prevent conflict with other students. 

## Setting up Github and Git

1. Quick Review of Terms: 
	1. "Git" refers to a program that allows the user to use robust version control on their files. The program is typically used on the "command line" but also has GUI versions available.
	2. "Github" is a popular website that interface with said program to host code.
	3. "command-line application" refers to an application that you use in a terminal application. Git for Windows comes bundled with "Git Bash" which is the main terminal application you will use to interface with git. On Mac, you will use the app named "Terminal".
	4. "Repository", usually referred to as "Repo", refers to a project that is hosted on Github containing all the code under version control.
2. [Getting Started with Github](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)
	1. Follow Part 1: Configuring your Github account
	2. **Note:** It is advised that you set your username to something professional or close to your name, not your goto username for sketchy forums on the internet.
	3. Review Part 2: Using Github's tools and processes
3. On [Download Git](https://git-scm.com/downloads) select your operating system under Downloads
	1. *Windows:* Under Standalone Installer, click "64-bit Git for Windows Setup". Click on the downloaded exe file. The defaults in the installer are generally fine so you can click next several times until it is installed.
	2. *Recommended Mac:* 
		1. Install [Homebrew](https://brew.sh/). See the website for more details.
		2. Install Git. Open terminal and type `brew install git`
		3. Install Git credential manager. Open terminal and type `brew tap microsoft/git` followed by `brew install --cask git-credential-manager-core`
	3. *Alternative Mac*: If you don't want to do the above, visit [Downloads for MacOS](https://git-scm.com/download/mac) and just click on the "Binary Installer". After downloading, right click on the file and click install. You will have to do a more complicated set up for connecting with Github later on. Then follow [Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token0). You will need this personal access token when Git asks for your password.
	4. If you don't want to use the command line, install [Github Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop). *Note:* this guide will provide no support for this option.
4. [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
	1. In particular focus on "Set your username in Git" and "Set your commit email address in Git"
	2. **Note:** The username in "Git" is different from the username in
	  "Github". Please set your "username" in Git as your full name (e.g. the
	  one you would put in Academic papers)
	3. **Note**: The email you set here is used to associate the changes you
	  make with your "Github" account. Please read the "Setting your commit
	  email address in Git" carefully.
5. Clone this repo
	1. Navigate to the directory that you will want to store the folder containing these notes (i.e. in Windows Explorer or Finder)
	2. Right click and select
		1. *Windows*: Git Bash Here. This will open up a black terminal program allowing you to access the "Git" command.
		2. *Mac*: Open Terminal to this folder (*Note:* you have to right click the folder itself in Finder, then click New Terminal At Folder. If your version of MacOS is a bit older, the option may be in the Services submenu after right clicking)
	3. Run `git clone https://github.com/alihaiderismail/Money-and-Banking-Theory-Notes.git` on the command line
6. [Download the LyX document processor](https://www.lyx.org/)
7. [How to use Lyx](https://wiki.lyx.org/LyX/Tutorials)
	1. You should navigate to Tools->Preferences->Identity and put in your name and email
8. [Set up Lyx to use Git](https://www.lyx.org/HowToUseGIT)
	1. This essentially boils down to using the File->Version Control menu in LyX which makes interacting with Git very easy.

## Workflow 

The workflow should look like
1. **Before editing files:** 
	1. Open your terminal application to the folder you cloned the repo to (see 5ii). You should see the word *(main)* in blue after the folder. If not you are not in the right folder!
	2. Run `git pull` to get the most up-to-date notes, authenticating if necessary.
2. Edit the Lyx file(s)
3. Click on File->Version Control->Check in Changes
	1. If prompted "save your changes"
4. You will be prompted with "LyX VC: Log Message". Fill in a short 50 character description of what you did. Then click Ok.
	2. Please actually describe the changes. "*Updated notes*" is not an appropriate commit message. 
5. In the terminal program, type `git push` to send your changes back to Github
	1. *If following the recommended installation*: You can type in your Github username and password, and two-factor authentication if you set it up.
	2. *If not*: Type in your Github username and *personal access token* (see 3.3).

## Tutorial on Using Git

[Software Carpentry's Intro to Git](https://swcarpentry.github.io/git-novice/) is a nice tutorial to learn step by step how Git works. Check it out to learn more.

# Course Website

* Visit [22F-ECON-221A-LEC-1](https://bruinlearn.ucla.edu/courses/140538) on BruinLearn (only accessible to UCLA students enrolled in the course) for more information.

# Copyright

Lecture Notes Copyright (c) 2022 Saki Bigio

Readme Copyright (c) 2022 Ali Haider Ismail
