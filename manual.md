
Intro
=================
Git is a version control software used to manage projects. Version control is a means of tracking, updating, and managing software across multiple systems and developers. A project is kept in a central repository and using git can be updated and changed on the fly. If two people are working on the same code they won`t lose one persons code. With version control both users can make changes to code and upload their versions. They can even chose to merge their code together. 
//Needs revision


Table of Contents
====================



Before You Start
========================
There are a few important things you need before you start:

1.  Access to a computer with Windows/Linux/Mac.
2.  Sufficient permissions to add and delete files (should be reworded to sound less technical)
3.  Some knowledge of the command line
4.  An Internet Connection
5.  A Github account




Steps/Instructions
====================
Steps to adding a repo go here


--Using Github.com--

	1. Using any web browser, enter https://www.github.com
	2. Create an account with your desired username and password.


--Setting up Git--

	1. How to install Git.
   
	   Installing Git on Linux
           ------------------------
		This installation guide will cover installing git on the more common 
 		distributions of linux.	    

		Step 1: Open up the command prompt


		Debian/Ubuntu/Mint
                  - 2. Type: apt-get install git
  	   
		Arch/Manjaro
   		  - 2. Type: pacman -S git
	
		Fedora/RHEL
		  - 2. Type: yum install git-core	  
	   

	   Installing Git on Windows
	   -------------------------
	   Refer to Troubleshooting

	   Installing Git on Mac
	   ---------------------
	   Refer to Troubleshooting
 	
	2. How to use Git Bash
	3. Configuring Git
	4. Configuring your name and email


--Adding Repositories to Github--

	1. Creating a repository
	2. Initializing a repository 
	3. Committing a repository
	4. Pushing to Github
	5. Pulling from Github
	6. Merging Branches

Troubleshooting
======================
<br>Downloading git on windows</br>
<br>-----------------------------------------------</br>
<br>1. With any web browser navigate to http://git-scm.com/downloads</br>
<br>2. Select the download for windows</br>
<br>3. Save the file to any location</br>
<br>4. Double click the file to run it and follow the installation instructions</br>
<br>    Git is now succesfully installed onto windows </br>
<br></br>

<br>Downloading git on Mac</br>
<br>-----------------------------------------------</br>
<br>1. With any web browser navigate to http://git-scm.com/downloads</br>
<br>2. Select the download for Mac</br>
<br>3. Save the file to any location</br>
<br>4. Double click the file to run it and follow the installation instructions</br>
<br>    Git is now succesfully installed onto Mac </br>

<br>Issues when committing code</br>
<br>------------------------------------</br>
<br>If you have any issues pushing a respository that isn't yours remeber to change the origin, you can change it with a few commands</br>
<br></br>
<br>$ git remote set-url origin http://github.com/username/repository_name</br>
<br></br>
<br>Set the username as your username and the repository name as the name of the repository you want to push</br>
<br>This changes the origin to your account so there are no conflicts</br>
<br>If the original repository is constantly being updated then you can also use the below command, again replacing username with your username and repository name with the name of your repository</br>
<br></br>
<br>$ git remote add personal http://github.com/username/repository_name</br>

Extra
=====================
<br>What is a repository: A place where your project files are stored.</br>
<br>What is Committing: Sharing your repository in its current state.</br>
<br>What is Forking: When someone wants to contribute to a piece of code they create a copy of the original code.</br>


Caching user credentials so you dont have to log in all the time.

What are Branches: 

<b>--Include a list of useful commands--</b>

<p>git init = Initialize repository</br>
<br>git help = Brings up list of commands</br>
<br>git status = Check repository to see what`s committed</br>
<br>git commit = Commit the repository to github</br>


