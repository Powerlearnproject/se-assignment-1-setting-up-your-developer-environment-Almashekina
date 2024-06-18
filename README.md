[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15291170&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Installing Windows 11

1. Check System Requirements
   - Ensure your PC meets the minimum system requirements for Windows 11.

2. Download Windows 11
   - Go to the [Windows 11 Download](https://www.microsoft.com/software-download/windows11) page and download the Media Creation Tool.

3. Create a Bootable USB Drive
   - Run the Media Creation Tool.
   - Select "Create installation media" and follow the prompts to create a bootable USB drive.

4. Configure BIOS/UEFI
   - Insert the USB drive into the target PC.
   - Enter BIOS/UEFI setup (common keys: F2, F12, Delete, Esc).
   - Change the boot order to prioritize the USB drive.

5. Install Windows 11
   - Boot from the USB drive.
   - Follow the on-screen instructions to start the Windows 11 installation.
   - Choose "Custom: Install Windows only (advanced)."
   - Select or create the partition for Windows 11 installation.

6. Configure Windows 11
   - After installation, configure region, keyboard layout, and network.
   - Set up a Microsoft account or a local account.
   - Complete privacy settings and device customization.

7. Install Drivers and Updates
   - Open "Settings" > "Update & Security" > "Windows Update."
   - Check for and install any available updates.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Download Visual Studio Code
Visit the Download Page:
Go to the Visual Studio Code Download page.
Select Your Operating System:
Download the installer for Windows, macOS, or Linux.
Install on Windows
Run the Installer:
Open the downloaded .exe file.
Accept the License Agreement:
Accept and click "Next."
Choose Installation Location:
Select destination folder and click "Next."
Select Additional Tasks:
Choose tasks like adding to PATH, creating a desktop icon, and click "Next."
Install:
Click "Install."
Launch Visual Studio Code:
Ensure "Launch Visual Studio Code" is checked and click "Finish."


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Step 1: Install Git
Download Git:
Visit the Git download page.
Select your operating system and download the installer.
Install Git:
Run the downloaded installer and follow the installation prompts.
On Windows, choose options like adjusting your PATH environment.

Step 2: Configure Git
Open Command Line:
Open Command Prompt (Windows).
Set Your Username and Email:
Configure Git with your username and email

Step 3: Create a GitHub Account
Sign Up:
Go to GitHub and sign up for a free account.
Complete the registration process and verify your email address.

Step 4: Initialize a Git Repository
Create a Project Directory:
Open your terminal or command prompt and navigate to your project directory
Initialize Git:
Initialize a new Git repository

Step 5: Make Your First Commit
Add Files:
Add your project files to the staging area
Commit Changes:
Commit your changes with a message

https://github.com/Almashekina/demo.git




4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Step 1: Download Python
Visit Python's Official Website:
Go to python.org.
Download the Installer:
Click "Downloads" and select the appropriate installer for your operating system (Windows, macOS, or Linux).

Step 2: Install Python on Windows
Run the Installer:
Open the downloaded .exe file.
Customize Installation:
Check "Add Python to PATH."
Click "Customize installation" for more options.
Select Features:
Ensure all necessary features (pip, IDLE, etc.) are selected.
Choose Installation Location:
Select the installation directory.
Install Python:
Click "Install" and complete the installation process.

Step 3: Verify Installation
Check Python Version

Step 4: Install Necessary Tools and Packages
Use Pip for Package Management:
Install packages as needed using pip


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Step 1: Check Python Installation
Verify Python Installation

Step 2: Download get-pip.py
Download get-pip.py:
Go to the get-pip.py download page.
Save the file to your local system.

Step 3: Install Pip
Open Terminal or Command Prompt:
Navigate to the directory where you downloaded get-pip.py.
Run get-pip.py:

Step 4: Verify Pip Installation
Check Pip Version

Step 5: Add Pip to PATH


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html



Step 1: Download MySQL Installer

1. Visit the MySQL Download Page:
   - Go to the [MySQL Community Downloads](https://dev.mysql.com/downloads/installer/) page.
2. Select MySQL Installer:
   - Choose "MySQL Installer for Windows."
3. Download the Installer:
   - Select "Windows (x86, 32-bit), MSI Installer" or "Windows (x86, 64-bit), MSI Installer" based on your system architecture.
   - Click "Download."

Step 2: Install MySQL

1. Run the Installer:
   - Locate the downloaded `.msi` file and double-click to run the installer.
2. Choose Setup Type:
   - Select the setup type. For most users, "Developer Default" is recommended. This installs MySQL Server, MySQL Workbench, and other useful tools.
3. Check Requirements:
   - The installer will check for required software. If anything is missing, it will prompt you to install it. Click "Execute" to install the required software.
4. Installation:
   - Click "Next" to proceed with the installation.
   - Review the installation summary and click "Execute" to start the installation process.

Step 3: Configuration

1. Server Configuration:
   - Choose "Standalone MySQL Server" and click "Next."
2. Type and Networking:
   - Select "Development Computer" and ensure the TCP/IP protocol is enabled. Click "Next."
3. Authentication Method:
   - Choose "Use Strong Password Encryption" and click "Next."
4. Accounts and Roles:
   - Set a root password and optionally create additional user accounts. Click "Next."
5. Windows Service:
   - Ensure "Configure MySQL Server as a Windows Service" is checked. Click "Next."
6. Apply Configuration:
   - Click "Execute" to apply the configuration settings.

Step 4: Complete Installation

1. Finish Installation:
   - Click "Finish" once the installation and configuration are complete.
2. Open MySQL Workbench:
   - You can open MySQL Workbench from the Start Menu to start managing your databases.

Step 5: Verify Installation

1. Log into MySQL:
   - Open Command Prompt and type:
     ```sh
     mysql -u root -p
     ```
   - Enter the root password you set during configuration.
2. Check MySQL Version:
   - Once logged in, verify the installation by checking the MySQL version
    


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   Step 1: Install Docker Extension for Visual Studio Code
Open Visual Studio Code:
Launch Visual Studio Code.
Open Extensions View:
Click on the Extensions view icon on the sidebar or press Ctrl+Shift+X.
Search and Install Docker Extension:
In the Extensions view search bar, type "Docker."
Find the Docker extension by Microsoft and click "Install."

Step 2: Configure Docker in Visual Studio Code
Open Docker Extension:
Click on the Docker icon in the Activity Bar on the left side of Visual Studio Code.
The Docker extension will display Docker containers, images, volumes, and networks.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Exploring Extensions for Visual Studio Code

1. Open Extensions View: Click on the Extensions icon or press `Ctrl+Shift+X`.
2. Search for Extensions: Use keywords like "syntax highlighting," "linting," "code formatting," or "version control."
3. Install Extensions: Click on an extension and click "Install."
4. Examples:
   - Syntax Highlighting: Install language-specific extensions (e.g., "Python").
   - Linting: Install linters like "ESLint" for JavaScript/TypeScript or "Pylint" for Python.
   - Code Formatting: Use "Prettier" for code formatting.
   - Version Control: Enhance Git capabilities with "GitLens."
5. Configure Extensions: Adjust settings in `File` > `Preferences` > `Settings` to customize behavior.
6. Usage:
   - Reload VS Code after installation.
   - Use features like syntax highlighting, linting, code formatting, and version control integration.
7. Explore More:
   - Look for extension recommendations.
   - Browse categories for more extensions.
   - Check reviews, ratings, and download counts for popular extensions.


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
