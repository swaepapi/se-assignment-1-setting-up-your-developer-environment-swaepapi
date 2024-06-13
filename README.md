[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15270064&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   Run a pc health check to see if your computer meets the minimum requirements of installing windows 11
   Ensure that all your important files and data are backed up to an external drive or cloud storage.
   Go to the official page of microsoft and download windows 11.
   Create a Bootable USB Drive;
   Insert a USB drive with at least 8 GB of storage into your PC.
   Run the Media Creation Tool the Select “Create installation media (USB flash drive, DVD, or ISO file) for another PC” and click “Next.” ,
   Choose the language, edition, and architecture (64-bit) and click “Next.”
   Select “USB flash drive” and click “Next.”
   Choose your USB drive from the list and click “Next.” The tool will download Windows 11 and create the installation media.
   The next thing is Installing  Windows 11
   Boot from USB:
   Insert the USB drive into the PC where you want to install Windows 11.
   Restart the PC and press the key that opens the boot-device selection menu (such as Esc/F10/F12) immediately after turning on the PC.
   Select the option that boots the PC from the USB flash drive.
   Setup Windows 11:
   When prompted, press any key to boot from the USB drive.
   Select your language, time, and keyboard preferences, then click “Next.”
   Click “Install now.”
   Enter Product Key:
   Enter your product key or select “I don’t have a product key” if you don’t have one. You can enter it later.
   Click “Next.”
   Accept License Terms:Check “I accept the license terms” and click “Next.”
   Choose Installation Type:Select “Custom: Install Windows only (advanced).”
   Select Partition:
   Choose the partition where you want to install Windows 11. If it’s a new installation, you may need to delete any existing partitions (this will erase all data on those partitions) and create a new partition.
   Select the partition and click “Next.”
   Installation:Windows 11 will start installing. Your PC will restart several times during the process.
   Configure Windows 11:After installation, follow the on-screen instructions to configure your settings, such as region, keyboard layout, and network settings.
   Sign in with your Microsoft account or create a local account.
   Customize your privacy settings and choose your preferences.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download 
   Open your preferred web browser and go to the Visual Studio Code website.
   Click the “Download for Windows” button. This will download the installer file (VSCodeSetup.exe) to your computer.
   Run the Installer; Once the download is complete, navigate to your Downloads folder or the location where the installer was saved and Double-click on the VSCodeSetup.exe file to launch the installer.
   The Visual Studio Code Setup wizard will open. Read through the License Agreement.
   If you accept the terms, click the checkbox labeled “I accept the agreement” and then click “Next.”
   Choose the destination folder where you want to install VS Code. The default location is typically C:\Program Files\Microsoft VS Code.
   Click “Next” to continue.
   You will be presented with several additional tasks you can set up during the installation:
   Create a desktop icon: Check this if you want a shortcut icon on your desktop.
   Add to PATH : This option allows you to run VS Code from the command line using code. This is highly recommended.
   Register Code as an editor for supported file types: This option sets VS Code as the default editor for specific file types.
   Add "Open with Code" action to Windows Explorer file context menu: This allows you to right-click on any file and open it directly in VS Code.
   Add "Open with Code" action to Windows Explorer directory context menu: This allows you to right-click on any folder and open it directly in VS Code.
   Check the options you prefer and click “Next.”
   Review your setup choices and click the “Install” button to begin the installation process.
   The installation process will take a few moments. Once it’s complete, you will see a setup completion screen.
   Check the box labeled “Launch Visual Studio Code” if you want to start VS Code immediately after installation.
   Click the “Finish” button.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   Go to the official Git website and Click the “Download for Windows” button. This will download the Git installer and run the Installer:
   Locate the downloaded installer  in your Downloads folder and double-click to run it.
   Follow the following steps:
    Click “Next” on the initial setup screen.
    Select the destination location  and click “Next.”
    Select the components you want to install  and click “Next.”
    Choose the start menu folder and click “Next.”
    Select a default editor for Git (e.g., Vim, Notepad++, VS Code) and click “Next.”
    Adjust the PATH environment and other settings and click “Next.”
    Choose HTTPS transport backend and credential manager options and click “Next.”
    Continue through the remaining steps and click “Install.”
    Once the installation is complete, click “Finish.”
   Configuring Git
    Open Git Bash which is installed along with Git. You can find it in your start menu.
    Configure your username by typing the following command git config --global user.name "Your Name" then input your git hub username in the quotes 
    Configure your email by typing the following command git config --global user.email "your_email@example.com" and input your githaub email
  Check your configuration by typing git config --list

   Creating a GitHub Account:
    Go to GitHub and Click “Sign up” in the upper-right corner.
    Enter your email address and click “Continue.”
    Follow the prompts to create a username, set a password, and verify your account.
    Initializing a Git Repository and Making Your First Commit
   Create a New Project Directory:
    Open Git Bash
    Navigate to the location where you want to create your project directory: by typing cd path/to/your/directory
    Create a new directory: mkdir my-project the cd my-project
    Initialize the repository by typing git init
   Create Your First File:
    Create a new file, e.g., README.md:
    Add the File to the Staging Area: git add README.md
    Commit the staged file: git commit -m "Initial commit"
   Create a New Repository on GitHub:
    Go to your GitHub account and Click the “+” icon in the upper-right corner and select “New repository.”
    Enter a name for your repository.
    click “Create repository.”
   Link Your Local Repository to GitHub: In Git Bash or Command Prompt, add the GitHub repository by pasting the following comand:
   git remote add origin "paste the link to the repo here"
   Finally Push your local repository to GitHub by pasting this commandm;git push -u origin master

4. Install Necessary Programming Languages and Runtimes:
  Install Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Open your preferred web browser.
  Visit the official Python website: https://www.python.org/.
  On the Python homepage, click the “Downloads” tab.
  The latest version for Windows should be highlighted. Click the “Download Python ” button. This will download the Python installer
  Navigate to your Downloads folder or the location where the installer was saved and Double-click on the downloaded file to run the Python installer.
  The Python setup wizard will open.
  Check the box that says “Add Python  to PATH” at the bottom of the setup window. This allows you to use Python from the command line.
  click “Install Now.”
  The installer will copy files and set up Python on your machine. This may take a few minutes.
  Once the installation is complete, the setup wizard will show a “Setup was successful” message. Click “Close” to exit the installer.
  Verify Python Installation by opening command prompt and checking the python version by typing 'python --version'
  install python extension on vs code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Open your preferred web browser.Go to the get-pip.py file in your browser and right-click on the page and select “Save As” to download the get-pip.py script to your computer.
   Open Command Prompt and Use the cd command to navigate to the directory where you saved get-pip.py. For example: cd C:\Users\YourUsername\Downloads
   Install pip by running the following command: python get-pip.py
   After the installation is complete, verify that PIP is installed by running:  pip --version
   You should see the PIP version displayed, confirming that PIP has been installed successfully.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Open your preferred web browser.Visit the official MySQL website: https://dev.mysql.com/downloads/installer/.
   You will see two options: "Web" and "Full". The "Web" version is smaller and requires an internet connection during installation to download the necessary components, while the "Full" version includes all the components in one package.Click the "Download" button for your preferred version (it is recommended to use the "Web" version unless you want all features offline).
   You may be prompted to sign up for an Oracle account, but you can click on “No thanks, just start my download” to download without signing up.
   Navigate to your Downloads folder or the location where the installer was saved.Double-click on the downloaded file to run the installer.
   The MySQL Installer will open and You will be presented with several setup types:
   Select “Developer Default” or “Server Only” depending on your needs and click “Next.” 
   The installer will check for required software. If any software is missing, the installer will prompt you to install it.
   You will be taken to the “Select Products and Features” page. Ensure the desired products are selected and click “Next.”
   The installer will download and install the selected products. This process may take some time.Once the installation is complete, click “Next” to proceed
   Click “Next” on the configuration overview screen to begin configuring the MySQL Server.Choose “Standalone MySQL Server / Classic MySQL Replication” and click “Next.”
   Select the appropriate configuration type (usually “Development Computer” for a local setup).Click “Next.”
   Choose the preferred authentication method (the default "Use Strong Password Encryption" is recommended) and click “Next.”
   Set the root password (make sure to remember it) ands Configure MySQL Server as a Windows Service and name the service (default is usually fine).click next
   Review the configuration settings and click “Execute” to apply them. Once the configuration is applied, click “Finish.”
   The installer may prompt you to configure other products (such as MySQL Workbench)
   Once all configurations are complete, click “Finish” to exit the installer
   Open the MySQL Command Line Client from the Start menu.then enter the root password you set during the configuration. and you should now be logged in to the MySQL command line interface.
   Run a simple query to verify the installation: SHOW DATABASES;
   You should see a list of default databases. This means you have installed sql successfully 

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   Launch VS Code In the Activity Bar on the side of the VS Code window, click the Extensions icon
   In the Extensions view, there is a search box at the top. Type the name or keyword of the extension you want to install. For example, to install the Python extension, type “Python”.
   Browse through the search results and click on the extension you want to install
   Click the “Install” button on the extension’s detail page. VS Code will download and install the extension.
   You may see a notification indicating the progress and completion of the installation.
   After installation, you can view and manage your installed extensions by clicking the “Installed” tab in the Extensions view.
   Some extensions have customizable settings. To configure these, click the gear icon (⚙) next to the extension name and select “Extension Settings”.This will open the settings editor where you can adjust the extension’s options.
   Some recommeded extensions include;
   Language Support:Python,Dart,
   Code Formatting:Prettier
   Version Control:GitLens, Git History
   Utilities:Live Server, Path Intellisense
   Themes and Icons:monokai dark,github dark

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
