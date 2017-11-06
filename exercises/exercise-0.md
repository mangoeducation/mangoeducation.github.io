# Exercise 0 - Introduction

Follow the steps to install Python 3. As Python 2 is retiring in a few years, it's only logical to use Python 3!

## Installation - Python 3
### Windows
* **Step 1** - Head over to this [Python download page](https://www.python.org/downloads/) and download the installer for Python 3.6.x.

* **Step 2** - Double click the installer and begin installing.
* **Step 3** - You can either choose to set the environment variables (`PATH` and `PATHEXT`) upon installation or [set it manually](https://docs.python.org/3/using/windows.html#configuring-python) once the installer finishes.
* **Step 4** - Open a command prompt and verify that `python -V` shows the version installed. If you get any errors, bug Aru and ask him to set the env variables for you!

### Linux
* **Step 1** - It's already installed! Just fire up a terminal and check the version.
* **Step 2** - If your Python version is 2.x.x, you can install Python 3 using the following commands in your terminal (for debian based distributions).  

        $ sudo apt-get update
		$ sudo apt-get install python3.6
        
* **Step 3** - For LTS versions use the following repository.

		$ sudo add-apt-repository ppa:fkrull/deadsnakes  
      
## Installation - Sublime Text 3
### Windows
* Download [here](https://www.sublimetext.com/3).

### Linux
* Use the following commands in your terminal.
		
		$ sudo add-apt-repository ppa:webupd8team/sublime-text-3
    	$ sudo apt-get update
    	$ sudo apt-get install sublime-text-installer`

---
[Home](/) | [Next](/exercises/exercise-1)