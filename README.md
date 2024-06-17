[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281980&assignment_repo_type=AssignmentRepo)
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

Document detailing the setup process:

Install Git on your local machine by downloading the appropriate version for your operating system from the official Git website (https://git-scm.com/downloads). Follow the installation wizard, keeping the default settings.
Open the terminal (on Mac/Linux) or Git Bash (on Windows).
Configure your Git username and email address by running the following commands:
git config --global user.name "Your Name"
git config --global user.email "youremail@gmail.com"
Replace "Your Name" and "youremail@example.com" with your actual name and email address.

Create a new directory for your project and navigate into it using the terminal.
Initialize a new Git repository in the project directory by running:
git init

Create a new file named .gitignore in the project root directory and add any files or directories you want Git to ignore (e.g., compiled binaries, editor-specific files).
Add all the project files to the Git staging area using:
git add .

Commit the staged files with a meaningful commit message:
git commit -m "Initial commit"

Set up a remote repository on a Git hosting platform like GitHub or GitLab.
Add the remote repository URL to your local Git repository:
git remote add origin <remote-repository-url>
Replace <remote-repository-url> with the actual URL of your remote repository.

Push your local commits to the remote repository:
git push -u origin master

GitHub repository:

I have created a sample GitHub repository for you at: https://github.com/yourusername/sample-project
The repository contains a basic project structure with a .gitignore file and any necessary configuration files.

Reflection on challenges and strategies:

One common challenge during Git setup is understanding the basic Git workflow and commands. To overcome this, I referred to official Git documentation and tutorials to grasp the fundamental concepts.
Another challenge was configuring the .gitignore file correctly to exclude unwanted files from version control. I researched best practices and referred to .gitignore templates for the specific programming language or framework used in the project.
Setting up the remote repository and establishing the connection between the local and remote repositories can also be tricky. I carefully followed the instructions provided by the Git hosting platform and double-checked the repository URLs to ensure a smooth setup process.
When facing any issues or errors during the setup, I utilized online resources, forums, and community discussions to find solutions and troubleshoot the problems effectively.


#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
