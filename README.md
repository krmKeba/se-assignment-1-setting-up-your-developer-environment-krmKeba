[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15265616&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

# A documentation of detailed setup process with step-by-step instructions

> Installation of Operating System (Windows 11)

- Firstly checked if my machine was compatible by searching msinfo in search slot on taskbar to see if machine meeted (64bit processor, 4GB ram) requirements
- Secondly I made sure my machine was connected to internet
- Backed up valued contents to cloud service (oneDrive)
- Visited https://www.microsoft.com/software-download/windows11 and chose recomended download option
- Used installation Assistant becouse i was upgrading from windows 10
- Downloaded media creation tool and ran to perform installation onto an external memmory which was 1TB
- Inserted external memmory and booted from it 
- Flollowed on screen instructions to complete installation
- I followed the prompts to select my region, keyboard layout, and signed in to my Microsoft account
- Chose my privacy settings and let Windows 11 complete the final setup steps
- Installed any available updates in Settings
- Recoverd backed up contents from previous OS from cloud

> Installation of IDE (VS code)

- I firstly downloaded Visual Studio Code using: https://code.visualstudio.com/Download
- Secondly I navigated downloaded package in explorer and installed
- Launched VS code and creatrd a folder from the welcome screen
- Created a file after executing a folder 
- Searched and installed extentions for coding languages like Python, html and java
- Set my settings to auto save 
- Customized VS code in settings/preferences (turned it to dark mode)  
 
> Setting up version control system (Git)

- Downloaded the installer using: https://www.git-scm.com/downloads
- Installed Git from navigated downloaded package installer in explorer
- I open Gitbash and ran as admin to configure
- configured buy entering the following commands: 
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
- Opened prefered browser and created a github account using:  https://github.com/
- Created a new repository by clicking '+' and 'new repository' at the top right corner and filled in the details
- I initialized a git repository and push using the following communds:
   cd /path/to/your/project
   git init
   echo "# My Project" > README.md
   git add README.md
   git commit -m "Initial commit"
   git push -u origin master

> Installation of necessary programing languages (Python)

- Firstly I downloaded Python installer on: https://www.python.org/downloads/
- Located the downoaded file in explorer and ran
- I added path on the config window and pressed install now
- Opened cmd in start manue and entered the following commands to verify installation of Python and its extention pip:
   python --version
   pip -- version

> Configuration of data base (MySQL)

- I firstly downloaded MySQL installer on: https://dev.mysql.com/downloads/windows/installer/5.7.html
- Secondly I installed and ran MySQL package after navigating it in the explorer
- Opened MySQL Command Line Client and created a new MySQL user and granted privileges with the following command:
   CREATE USER 'username'@'localhost' IDENTIFIED BY 'password';
   GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost' WITH GRANT OPTION;
   FLUSH PRIVILEGES;
- Created a new database and exited MySQL using the following commands:
   Create a new databas;
   exit;

> Explore Extensions and Plugins

- I found Prettier usefull in web development since its a formatter that supports verious languages
- Pylance is an extention that is a fast supporter of python
- Django is a helpfull tool which i use its web development frame works and it make the process fun and much easier
  
