[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15289815&assignment_repo_type=AssignmentRepo)
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

  #                                 ANSWERS
For my operating system I chose Microsoft Windows,after that installed visual studio code,Github,python,additional packages like pip(python) and MySQL.And thses are the following steps i took to install them:
#VISUAL STUDIO CODE
# 1.DOWNLOADING AND SETTING UP VS CODE
 I went the website  visual studio code and clicked on download and chose the one for windows and waited for it to be installed.
 Once the download was done ,I run the installer and accepted all the license agreement and allowed it to make changes to my device.I left the location as default i followed the step by step instractions and clicked install and clicked finish.
 I opened my visual studio code and explored.After that i clicked on the extensions view icon and explored.I then installed the following extensions.
 -Python which is a programming language
 -Python debugger,it integrates with VS code to allow variable inspection.
 -Prettier which ia a code formatter that supports multiple languages like CSS,JavaScripts etc
 I know how to create a new terminal in VS code and how to run a code.
# 2.INSTALLING AND SETTING UP GITHUB 
 I went to the git websit and downloaded the version suitable for my operating system.
 After it finished downloading i opened commad prompt and typed git --version and pressed enter to check the version that i downloaded which is 
 In commmad prompt i typed git config --global user.name and entered my username and clicked enter.
 Then typed git config --global user.email and entered my email.
 And then it asked me th create a password and i did that.
 I then cloned a repository that we created during a lesson and to do that i went to GitHub and chose it and then clicked the green code button and coppied the SSH URL.
 Using commad prompt i typed git clone and copied the URL that i copied from GitHub.
 Then to make changes to the file in my repository i typed git add .enter,then commited by typing git commit -m and added a message.
 I then to push the changes i made i typed git push origin main.
 Then i pulled the changes made by typing git pull origin main.
# 3.INSTALLING AND SET UP OF PYTHON
 I went to the python official website and downloaded the lastest version of python suitable for my operating system.
 After the download was done ,i opened commad prompt and typed python  --version and pressed enter and the lastest version was the one i installed.
 I also createc a virtual environment
 I also installed pip and upgraded it by typing pip install which i can use to install other python packeges .
# 4.INSTALLATION AND SET UP OF MYSQL
 I went to the page MySQL community  downloads and downloaded the lastest version of MySQL 
 And then i chose the developer default setup type which includes MySQL server and other necessary components .
 Then i chose a setup type and i wennt for Server only,and configured MySQL .It then asked me to set a root password ,which i did and then clicked on install and waited for it to finish.
 To test my installation i opened my commad prompt and typed mysql-u root-p to coonect to MySQL server ,after i clicked enter it asked for my root password which i created earlier,and i did that.
 Where i created a database by typying CREATE DATABASE and entered the name of the database and then i granted priviledges to the database. 
 To verify the status and version of MySQL and typed mysqladamin -u root -p status and it showed me the lastest version of mysql.
  #               REFLECTION ON CHALLENGERS AND  SOLUTIONS ENCOUNTERED 
The installation process that gave me problems was MySQL ,because someone that used to use my computer installed it before and never deleted the file .So when  creating a root password ,i was asked to enter the current one which i had no idea of .
I watched some videos on youtube and did some research ,So i had to uninstall the MySQL that i had installed and delete the mysql files that where in the computer and install it again.
This process helped me and when i tried to configure mysql again it worked out ,it asked me to enter new root password.

 



