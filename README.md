[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15283270&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Documentation of windows 11 instalation:
-On my default browser, that is chrome, I followed this link  https://www.microsoft.com/software-download/windows11. 
- I followed the instructions to check my PC health and determine its compatibility with windows 11. I navigted to my PC health check and did so.
- After making the necessary  adjustements and confirming everything was okay, I navigated to the 'create windows 11 instalation media' and clicked download so as to download it onto aUSB flashdrive. 
- I got a prompt to get  few things ready which I accepted. I was then prompted to select the language, edition and media to use.
- I then inserted my USB flahsdrive into my PC and selected USB flashdrive afterwhich it downloaded amd copied the media onto my USB flashdrive.
- I then restarted my computer  and pressed th key that turns in the boot-device selection menu and selected the option that boote sthe PC from the flashdrive.
- Once the windows setup started, I clicked install now and then selected windows 11 pro version, then selected 'custom instalation type', then waited fro it to install windows.
- I then turned off the computer to remove the flashdrive then turned it back on again.
- I the followed th prompts and toggled the prefered selection afterwhich my laptop was ready to go. 


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

Documentation of Visual studio code instalation:
- Firstly, I downloaded the visual studio code by visiting the official Visual Studio Code website (https://code.visualstudio.com/) on my default browser that is Chrome.
- I then navigated my way to the "Download for Windows 10,11" button seeing as my OS is windows. I then proceeded to download the installer file.
- Once the download was complete, I was able to locate the downloaded file on my downloads folder on my local device and double-clicked it to open it and run as administrator.
- An instalation wizard popped up from which I was able to follow the prompts. I then proceeded to read the license agreement and press okay then clicked install and allowed it to be installed on my device then clicked finish once it was done setting up.
-After the installation was complete, I was able to launch the visual studio code on my computer by navigating to the start search panel and locating it there.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
    
Documentation of Git Installation and configuration:
Installation:
- On my browser i.e Chrome, I visited the site throguh this link htps://windows.github.com and downloaded the 64 bit option for windows setup. Once downloading was complete, I clicked on the file which led me to the installation section and I was able to click install then finish.
- Once that was complete I navigated to my Git bash where I opened it as an administrator.

Configuration:
- On the initial page of the gitbash, I checked the version by typing in 'git --version'
- I then proceeded to key in my name by using the prompt 'git config --global user.name “[firstname lastname]”' and my email using the prompt 'git config --global user.email “[valid-email]”'.

Creation of Git hub account:
- I installed Git hub by visiting 'github.com' on my browser and signing in by enterin gmy email and pass word.

Creating and initializing a git repository:
- once inside git hub, I locate the repoitories tab on my profile and clicked it.
- I then clicked on the "new" icon ojn the right side of the page.
- I thne created  repository name , added a description then clicked on 'create repository' to create the repo.
- I then initialized the repository by entering the command 'git init'.

Making my first commit:
- I propmted 'git status' into my git bash to check if there were any commits yet.
-  then proceded to key in 'git add "file name"' then keyed in 'git status' yo keep track of the changes that have been made.
- To commit the files, I then keyed in 'git commit -m "message"'
- I then linked it to my github by keying in the command 'git remote add origin' and pasted my git hub repo.
- To push, I then entered the command 'git psh -u origin master' and pressed enter.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Documentation of python installations:
- On my browser i.e Chrome ,I visited the official python page through the following  link : http://wwww.python.org.
- Here, I clicked on the downloads tab which suggested the latest version of python. That is 3.12.4.
- I then selected this option and waited for it to download onto my laptop.
- Once downloaded I located the file and double clicked on it to run the installer.
- I was then faced with two options of either "Install Now" and "Customize installation". I Checked the box that suggested "Add Python X.Y to PATH" at the bottom of the installer window to ensure that Python was addedto my system's PATH, making it accessible from the command line.
- I then Clicked on "Install Now" to start the installation.
- To install compilers, interpreters amd runtimes, I selected the "Customize installation" and  selected optional features to ensure that "pip" (Python's package installer) is checked, as well as "IDLE", "Documentation", and "py launcher" were present.
- I then Waited for Installation to Complete whic took a few minutes afterwhich I received amessage that the steup was succesful.I then clicked "Close" to exit the installer.
- To Verify Installation, I Opened the Command Prompt and pressed Win + R, type cmd, and press Enter.
 -I then typed python --version and pressed Enter after which was able to see the Python version that had beeen installed, indicating that Python was installed correctly.
- I then Typed pip --version and pressed Enter to check if pip, Python's package installer, had also been installed correctly.
- On VS Code I was able to intsall various IDEs for python on the extensions marketplace.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Documentation of pip installation:
- To install package managers such as pip I opened git bash and run the command "python --version" to verify the python installation after which I was able to see the installed python number.
- Using curl to download the get-pip.py script. In Git Bash, I entered the following command and pressed Enter: "curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py"
- I then run the followign command "python get-pip.py" to install pip which I then verified by checking the pip version through the following command "pip -- version".
- For troubleshooting, for any issues encountered I ensured that Python had been correctly installed and added to my system PATH and ensured that I had the necessary permissions to install packages and modify the system PATH.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Documentation od MySQL download and Installation:

- To install MySql database, I first was able to access the downloading website on https://dev.mysql.com/downloads/windows/installer/5.7.html where I selected the full My SQL package for downloading.
- After selecting the version  preferred I was provided with an option of signing up to My SQL community account which I opted to do at a later stge. Therefore, I simply selected the option to just start my download at the bottom of the page whic prompted the download to begin immediately.
-  I then had to wait a few moments for the installer to configure and prepare the installation process.
- In the MySQL Installer, I was able to see several setup options:
Developer Default: Includes MySQL Server, MySQL Workbench, MySQL Shell, and other development tools.
Server Only: Installs only the MySQL Server.
Client Only: Installs only MySQL client programs.
Full: Installs all MySQL products.
Custom: Allows you to select which products to install.
- I opted to choose the server only option and proceeded to execute to begin the installation process.
- Once the status was labeled as complete, it was now time to configure the database and I was prompted to configure MySQL products. I then Clicked "Next" to proceed.
- For availability I opted to chose the stand alone server and clicked next, For Type and Networking:
I opted to Choose the configuration type "Development Computer" and set the default port number to 3306.
- For the Authentication Method, I opted to Choose the default authentication method that is "Use Strong Password Encryption for Authentication" and set the root password. 
- I skipped ythe accounts and roles staged and opted to run My SQL as a windows service whose default name I set as "MySQL80" and clicked next.
- On the loggin options I was able to select my prefered logs then clicked next to reach the advanced option section which I skipped and went straight to the configuration section. 
- The installer then showed a summary of the configuration. I Clicked "Execute" to apply the configuration which led me to the complete installation stage.
- Once the configuration was applied, I clicked "Finish".
- I then opened the Command Prompt to verify my installation by typing in " mysql -u root -p" and pressed Enter.
- I then Entered the root password set during the configuration after which I was able to see the MySQL command prompt, indicating that MySQL is installed and running.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

- The first step was to launch VS Code the to access the Extensions View.
- I then browsed the extensions marketplace to find relevant extensions such as Python image preview, Python debugger, Pyhton, Pylance, mplstyle, fluuter, dart, code runner e.t.c. on which I clicked on install to add them to VS code.
- Recommended Extensions for Enhanced Functionality on VS Code included syntax Highlighting where I opted to install "Python" by Microsoft. It provides rich support for the Python language, including IntelliSense, linting, and debugging.
- For linting I opeted for Pylint to ensure that "Python" by Microsoft is installed, which includes Pylint integration.
- For code Formatting I opted for Black. For Python, I installed "Python" by Microsoft, and then installed Black by adding it to your Python environment (pip install black).
- For version Control Integration I opted for GitLens by Searching for and installing "GitLens" by Eric Amodio. It supercharges the built-in Git capabilities with advanced features.
- I also installed Git Grap which Provides a visual representation of your Git repository. I Searched for and installed "Git Graph" by mhutchie.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Challenges faced dduring the set up and strategies employed to overcome them include:
1. Various syntax errors when running verification codes and prompts on various IDEs such as Git bash and command prompt which caused errors and caused various repetitions of intsallation and configuration processes. 
- This was mitigated by making good use of artificial intelligence platforms such as Chat GPT and the LMS AI chatbot Gemini by simply copying the troublesome area and pasting it to try and troubleshoot the problem.
2. Another major challnge was the duration of time taken to install large files such as MySQL databases onto my device. They surprisingly took a very long time/ I know understand that this may have been caused by traffic in my device and even slow internet. 
- I was able to overcome this challenge by following the instruction learnt in class on how to optimize my device and how to clear some redundant cached files that may have been causing unnecessary traffic.


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
