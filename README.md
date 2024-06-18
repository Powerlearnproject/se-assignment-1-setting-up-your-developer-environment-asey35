[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292270&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Downloading Windows 11
Visit the official Microsoft website for Windows 11 downloads: Microsoft Software Download Page
Choose between the Media Creation Tool, ISO file download, or the Windows 11 Installation Assistant based on your preference and needs.
Using the Media Creation Tool
Run the Media Creation Tool as an administrator.
Accept the license terms.
Choose "Create installation media for another PC," then select "Next."
Select the language, edition, and architecture (64-bit) for Windows 11.
Choose to use a USB flash drive or save an ISO file to your PC.
Using an ISO File
Download the ISO file to your PC.
To create a bootable DVD, locate the downloaded ISO file, right-click it, select "Properties," and then "Burn disc image." Alternatively, you can mount the ISO file directly to upgrade your current OS to Windows 11.
Using the Windows 11 Installation Assistant
The Installation Assistant is designed for upgrading a Windows 10 PC to Windows 11.
Ensure your PC has Windows 10, version 2004 or higher, and at least 9 GB of free disk space.
Download and run the Installation Assistant as an administrator.
Accept the license terms and initiate the installation process.
Creating Installation Media
If using a USB flash drive, attach a blank USB with at least 8GB of space. Remember, all content on the flash drive will be deleted.
If using an ISO file, you can burn it to a DVD or mount it directly for installation.
Installing Windows 11
Insert the USB drive or DVD into your PC and restart it.
Enter the BIOS or UEFI settings to change the boot order to prioritize the USB drive or DVD.
On the "Install Windows" page, select your language, time, and keyboard preferences, then click "Next."
Follow the on-screen instructions to complete the installation.
Post-Installation
After installation, remove the installation media to avoid booting into the installer again.
Configure your new Windows 11 environment, including signing in with your Microsoft account and checking for updates via Settings > Windows Update.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/DownloadTo download and install Visual Studio Code, follow these steps:

Visit the Official Website: Go to the Visual Studio Code download page at https://code.visualstudio.com/Download.
Choose Your Version: Depending on your operating system, choose the appropriate version for download:
Windows: Click on the "Windows" button and download the executable file.
macOS: Click on the "macOS" button and download the .dmg file.
Linux: Click on the "Linux" button and download the .tar.gz archive.
Run the Installer:
Windows and macOS: Once the download is complete, run the installer. Follow the on-screen instructions to install Visual Studio Code. During installation, you can choose whether to add VS Code to your PATH so that you can launch it from the command line.
Linux: Extract the downloaded archive to your preferred location. Then, move the extracted folder to /opt or another directory in your PATH if you want to access it globally.
Launch Visual Studio Code: After installation, you can start Visual Studio Code by clicking its icon on your desktop or launching it from your applications menu.
Explore Features: Upon launching, take some time to explore the interface and learn about its features such as integrated Git support, debugging tools, and a wide range of extensions that can enhance your development experience.
Customize Your Workspace: Customize your workspace by adjusting settings, installing themes, and adding extensions relevant to your programming languages and workflow.
Visual Studio Code is a powerful, open-source code editor that supports a wide array of programming languages and offers extensive customization options through extensions. Its lightweight design makes it suitable for various development environments, from web development to software engineering projects.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   To set up a version control system using Git and GitHub, follow these steps:

Step 1: Install Git
Windows: Download and install Git from Git for Windows. During installation, ensure you check the option to use Git from the command line or terminal.
macOS: Install Git using Homebrew with the command brew install git.
Linux: Most Linux distributions come with Git pre-installed. If not, you can install it using your distribution's package manager, for example, sudo apt-get install git on Debian-based systems.
Step 2: Configure Git
After installing Git, configure your username and email address, which will be associated with your commits:
Step 3: Create a GitHub Account
If you don't already have one, go to GitHub and sign up for a new account.

Step 4: Initialize a Local Repository
Navigate to your project directory in the terminal and initialize a new Git repository:
Step 5: Connect Your Local Repository to GitHub
First, create a new repository on GitHub. Do not initialize it with a README,.gitignore, or License. Copy the URL of the new repository.

Then, link your local repository to the remote GitHub repository:
Step 6: Make Your First Commit
Add all your project files to the staging area:
Step 7: Push Changes to GitHub
Push your committed changes to GitHub:


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
To install Python and ensure you have the necessary tools to build and execute your code, follow these steps:

Step 1: Download Python
Go to the official Python website at http://www.python.org.
Look for the latest stable release of Python. As of my last update, Python 3.x is the current series, and Python 3.10 or newer is recommended for most users due to its performance improvements and new features.
Click on the "Downloads" section and find the installer for your operating system (Windows, macOS, or Linux).
Step 2: Install Python on Windows
Download the Windows installer (.msi file).
Run the installer. During installation, you'll see an option to "Add Python to PATH". Make sure this option is checked. This allows you to run Python from the Command Prompt without specifying the full path to the Python executable.
Complete the installation process.
Step 3: Install Python on macOS
Download the macOS installer (.pkg file).
Open the downloaded.pkg file and follow the on-screen instructions to install Python.
Optionally, you might want to install Homebrew, a package manager for macOS, which simplifies the management of Python versions and packages. You can install Homebrew by running /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" in the Terminal.
Step 4: Install Python on Linux
Most Linux distributions come with Python pre-installed. However, it's often a good idea to install a newer version alongside the system version. Here’s how you can install Python using a package manager:
Step 5: Verify Installation
Open a terminal or command prompt and type:
Step 6: Install Additional Tools
Depending on your project requirements, you might also need to install other tools like compilers (e.g., GCC for C/C++), virtualization tools (e.g., Docker), or database servers. These can typically be installed via your operating system's package manager or from the official websites.


5. Install Package Managers:
   If applicable, install package managers like pip (Python).
To install pip, the package installer for Python, follow these steps depending on your operating system:

For Windows Users
Manual Installation:
Download the get-pip.py file from https://bootstrap.pypa.io/get-pip.py.
Save the file in the same directory where Python is installed.
Open a command prompt and navigate to the directory where you saved get-pip.py.
Run the command python get-pip.py. This will install pip for your Python installation.
Verify Installation:
Open a new command prompt window.
Type pip --version and press Enter. This should display the version of pip installed.
For macOS and Linux Users
Pip is usually included with Python installations on macOS and Linux. However, if it's not available, you can install it using the following method:

Using curl:
Open a terminal.
Run the command curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py.
Execute the script with python get-pip.py.
Verify Installation:
In the terminal, type pip --version and press Enter. This should show the installed version of pip.
General Tips
Administrator Rights: If you encounter permission errors, try opening your command prompt or terminal as an administrator or superuser.
PATH Configuration: After installation, ensure that the Scripts directory of your Python installation is added to your PATH environment variable. This allows you to run pip from any command prompt or terminal session.
Multiple Python Versions: If you have multiple versions of Python installed, you might need to specify the version when running pip, e.g., python3 -m pip install package_name.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step 1: Access the MySQL Downloads Page
Once the MySQL website is accessible again, visit the MySQL Community Server downloads page at https://dev.mysql.com/downloads/mysql/. Scroll down to find the Windows section.

Step 2: Choose the Installer
Select the MySQL Installer for Windows. There are several options available:

MySQL Installer for Windows: A full installer that includes MySQL server, client, and workbench.
MySQL Server Only: If you prefer to manually select components or need a minimal setup.
Step 3: Download the Installer
Click on the download link for the installer that matches your version of Windows (32-bit or 64-bit). The installer size will depend on the components selected.

Step 4: Run the Installer
Once the download is complete, locate the installer file (usually named something like mysql-installer-community-VERSION.exe) and double-click it to run. Follow the on-screen instructions to proceed with the installation.

Step 5: Choose Setup Type
During the installation process, you'll be asked to choose a setup type:

Developer Default: Includes MySQL server, client, and workbench, along with sample databases and tools.
Server only: Includes only the MySQL server.
Client only: Includes only the MySQL client.
Custom: Allows you to select individual components to install.
For most users, especially those new to MySQL, the Developer Default or Server only options are recommended.

Step 6: Configure MySQL Server
The installer will guide you through configuring the MySQL server, including setting the root password and choosing the default character set. Pay close attention to these settings, as they cannot be changed later without reinstalling MySQL.

Step 7: Complete the Installation
Follow the rest of the prompts to complete the installation. The installer will automatically start the MySQL service after installation.

Step 8: Verify Installation
Open a command prompt and run the following command to verify that MySQL is installed correctly:
Additional Configuration
After installation, you might want to secure your MySQL installation by running the mysql_secure_installation script, which helps you set a root password, remove anonymous users, disable remote root login, and remove the test database.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Setting up a development environment with Docker or virtual machines can significantly streamline your development workflow by isolating project dependencies and ensuring consistency across different machines. Here's how you can get started with Docker on Windows, considering the information from the provided sources.

Setting Up Docker on Windows
Enable Nested Virtualization: If you plan to run Docker Desktop on a virtual machine, ensure nested virtualization is enabled. This is crucial because Docker Desktop runs a Linux VM under the hood to operate Docker Engine and containers .
Download Docker Desktop: Visit the Docker website and download Docker Desktop for Windows. Choose the version that suits your needs—either the standard version for personal use or the business version for professional environments.
Install Docker Desktop: Run the installer and follow the on-screen instructions. During installation, you might be prompted to enable Hyper-V and Containers optional features if they aren't already enabled. Agree to these prompts to ensure Docker can function correctly.
Start Docker Desktop: After installation, launch Docker Desktop. You might need to sign in with your Docker ID to activate your Docker subscription if you're using Docker Pro or Enterprise.
Verify Installation: Open a command prompt or PowerShell window and run docker version to confirm that Docker is installed and running correctly.
Running Docker in a VM or VDI Environment
If you're working within a virtualized environment (VM or VDI), ensure that nested virtualization is enabled on your VM provider (e.g., VMware ESXi, Azure VMs). Docker Desktop for Windows can run inside these environments, but support is limited to Docker Business customers and specific hypervisors .

Azure VMs: Ensure your VM size supports nested virtualization. Microsoft provides a list of VM sizes that support this feature. For optimal performance, consider using D4s_v5 or higher .
VMware ESXi: Similar to Azure, ensure your VM configuration supports nested virtualization. Docker Desktop can be installed and run inside these VMs, but support is primarily for Docker Business customers .
Considerations
Performance: Running Docker Desktop inside a VM can introduce performance overhead compared to running it natively on your host OS. Monitor your VM's performance and adjust resources as needed.
Networking: Be aware of potential networking complexities when running Docker inside a VM. You might need to configure additional network settings to ensure proper communication between your host and the Docker containers running inside the VM.
Updates and Support: Keep Docker Desktop and your VM software up to date to benefit from the latest features and security patches. Consult the documentation of your VM provider for guidance on updating nested virtualization capabilities.


8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
Exploring and utilizing extensions, plugins, and add-ons for your chosen text editor or IDE can significantly enhance your coding experience by introducing functionalities such as syntax highlighting, linting, code formatting, and version control integration. Here's how you can get started with exploring these enhancements:

For Visual Studio Code (VS Code)
Access the Marketplace: Open VS Code and navigate to the Extensions view by clicking on the square icon on the sidebar or pressing Ctrl+Shift+X. This opens the Extensions pane where you can browse through thousands of extensions.
Search for Extensions: Use the search bar at the top of the Extensions pane to find extensions related to your programming languages, frameworks, or desired functionalities. Popular searches include "Python", "JavaScript", "React", etc.
Install Extensions: Click on the Install button next to an extension to add it to your VS Code environment. Some extensions require additional setup or permissions, so follow any on-screen instructions.
Manage Extensions: After installation, you can manage your extensions by enabling or disabling them, accessing extension settings, or reading documentation directly from the Extensions pane.
For Other Code Editors
Sublime Text: Navigate to Preferences > Package Control to manage installed packages. Use the Package Control command palette (Cmd+Shift+P on macOS or Ctrl+Shift+P on Windows/Linux) to search for and install new packages.
Atom: Go to Settings > Install Packages to browse and install new packages. Use the Atom command palette (Ctrl+Shift+P or Cmd+Shift+P) to search for and install packages.
Notepad++: Extensions for Notepad++ are known as plugins. Go to Plugins > Plugins Admin to manage installed plugins. Search for and install new plugins from here.
Key Features to Look For in Extensions
Syntax Highlighting: Enhances readability by applying different colors to various elements of your code.

Linting: Checks your code for stylistic errors, bugs, and suspicious constructs.

Code Formatting: Automatically formats your code to adhere to a consistent style guide.

Version Control Integration: Simplifies working with version control systems like Git, allowing for easy commit, push, and pull operations directly from the editor.

Debugging: Provides tools to debug your code, stepping through execution, inspecting variables, and more.
Auto-Completion: Offers smart suggestions as you type, improving coding speed and reducing errors.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
Operating System Details
Operating System: [Insert Operating System Name and Version]
Kernel Version: [Insert Kernel Version if applicable]
Hardware Specifications
Processor: [Insert Processor Model and Speed]
Memory: [Insert Total Memory Size]
Storage: [Insert Primary Storage Type and Capacity]
Software Overview
Development Tools
Primary Text Editor/IDE: [Insert Text Editor/IDE Name]
Installed Version: [Insert Version Number]
Key Extensions/Plugins/Add-Ons: [List and brief explanation of each]
Secondary Tools: [List any secondary tools or editors used for specific tasks or languages]
Programming Languages and Runtimes
Python: [Insert Version] - Installed via [Method]
Java: [Insert Version] - Installed via [Method]
Node.js: [Insert Version] - Installed via [Method]
Database Management Systems
MySQL: [Insert Version] - Installed via [Link to installation guide]
Version Control System
Git: [Insert Version] - Installed via [Method]
Remote Repository: GitHub - Account setup and repository creation details
Package Managers
pip: [Insert Version] - Installed via [Method]
Commonly Used Packages: [List]
Configurations and Customizations
Text Editor/IDE
Theme: [Selected Theme and Reason]
Key Bindings: [Custom Key Bindings and Their Functions]
Extensions: Detailed descriptions of each extension, including its purpose and configuration settings.
Integrated Development Environment (IDE)
Project Templates: [Custom Templates Created and Their Usage]
Plugin Configurations: [Detailed Configurations for Plugins]
Programming Languages and Runtimes
Environment Variables: [Critical Environment Variables Set for Runtime]
Virtual Environments: [Details on Creating and Managing Virtual Environments]
Database Management Systems
User Accounts: [Details on Creating and Securing Database User Accounts]
Security Settings: [Security-Related Configurations]
Version Control System
Repository Structure: [Best Practices Followed for Organizing Branches and Tags]
Aliases: [Commonly Used Aliases for Repository URLs or Commands]
Package Managers
Package Aliases: [Commonly Used Aliases for Package Names]
Upgrade Strategies: [How Often and How Packages Are Upgraded]
Troubleshooting Steps
Common Issues and Solutions: List common problems encountered during setup and how they were resolved.
Documentation References: Links to external documentation or forums that were helpful in resolving issues.
Conclusion
This setup guide serves as a dynamic document that evolves over time as new tools and methodologies are adopted. Regularly updating this document ensures that it remains a valuable resource for both current and future team members, as well as for personal reference.

Feel free to customize this template according to your specific setup and preferences. Including screenshots, links to official documentation, and personal insights can further enrich this document, making it a comprehensive resource for anyone looking to replicate your development environment.


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
