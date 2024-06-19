Create the Installation Media
1. Head over to [Microsoft's official Windows 11 download page](https://www.microsoft.com/software-download/windows11)
2. In the "Create Windows 11 Installation Media" group, click "Download Now."
3. Run the program once it's finished downloading. Click "Accept" in the bottom-right corner of the window.
4. After a few seconds, you'll be on the Select Language and Edition screen. The only edition you can choose here is Windows 11, so just leave it at that.
5. Just let Windows select this for you by checking the box next to "Use the Recommended Options for This PC."
6. Select "Next" to continue.
7. On the next screen, you'll need to choose which media to use. Select "USB Flash Drive" and then click "Next" to continue. Remember that you must have at least 8GB of available storage space.
8. Next, select the flash drive you'd like to use. Once selected, click "Next" to continue.
9. The downloading process will begin. The amount of time it takes varies, but be prepared to wait for a bit. The good news is you can continue to use your PC while you wait.
10. Click the "Finish" button once downloading is complete, safely remove the USB drive from the computer, and then insert it into the computer that you want to install Windows 11 on.

Install Windows 11 From the USB Drive

1. Once the USB drive with the installation files is inserted into the destination PC, you'll need to set the boot order so that the computer loads the operating system from a location other than its hard drive. In this case, we want Windows to load the operating system from the USB drive.
2. When you're booting your computer, press the appropriate key to open the BIOS or UEFI controls. The key that you need to press differs between computers, but it's usually F11 or F12.
3. After you select the USB drive from the boot menu, your PC will reboot from the USB drive (instead of the hard drive) and ask you to begin the setup of the installation media by pressing any key.
4. First, you'll need to choose the language to install, the time and currency format, and the keyboard or input method. To change one of the preset options, click the down arrow and select an option from the drop-down menu. However, you'll rarely need to change anything here.
5. Click "Next" when you're ready to move forward.
6. Click "Install Now" on the next screen.
7. Windows will tell you that setup is starting, and then you'll be on the Windows Setup screen. This is the screen where you will activate your version of Windows. If you have your product key, enter it in the text box. If you don't, you can run a limited version of Windows by choosing "I Don't Have a Product Key" at the bottom of the window. If you choose the latter option, you can enter the product key at a later point to unlock everything.
8. If you entered your product key, click "Next" to continue. We'll select "I Don't Have a Product Key" in this example.
9. On the next screen, select the version of Windows 11 that you want to install. If you already have a product key, be sure to select the correct version, as product keys only work with their respective version. Once you select your version, click "Next."
10. We'll select "Windows 11 Pro" in this example.
11. Accept the license terms on the next screen by checking the box. Click "Next" to proceed.
12. You can then select to upgrade, which installs the new version of Windows while keeping your files, apps, and settings. We'll select "Custom: Install Windows Only (Advanced)" since we're doing a fresh install.
13. Finally, select where you want to install Windows. If your hard drive is new, it may say something like "Drive 0 Unallocated Space." If you've partitioned your drive, its name will reflect that.
14. The Wizard will now begin installing the Windows files. The length of this process varies from computer to computer and could take a bit of time.
15. Once finished, your computer will reboot. In some cases, you'll get stuck in a boot loop where the system tries to bring you back to the installation process. This happens because the system might be trying to read from the USB drive instead of from the hard drive that you installed the OS on. If this happens, remove the USB drive and restart the computer.

Developer Environment Setup Document

Introduction
This document outlines the steps I took to set up my developer environment. I've included configurations, customizations, and troubleshooting steps I encountered during the process.

Hardware and Software Requirements

- Operating System: I'm using Windows 11 on my laptop.
- IDE: I chose Visual Studio Code (VS Code) for my coding needs.
- Code Editor Extensions: I installed extensions for Python, JavaScript, and HTML/CSS to enhance my coding experience.
- Version Control System: I'm using Git for version control.
- Database: I set up MySQL for database management.
- Browser: I'm using Google Chrome as my default browser.

Step-by-Step Setup

1. Install Visual Studio Code

1. Download and Install: I downloaded the latest version of VS Code from the official website and installed it on my laptop.
2. Launch: After installation, I launched VS Code to start using it.



2. Install Code Editor Extensions

1. Open Extensions: I opened the Extensions panel in VS Code by clicking the Extensions icon in the left sidebar.
2. Extensions installed are: isort, Gitlens, anaconda, black formatter and code runner.



3. Install Git

1. Download and Install: I downloaded the latest version of Git from the official website and installed it on my laptop.
2. Configure Git: I configured Git by setting the username and email address using the following commands: bash
   git config --global user.name "Your Name"
   git config --global user.email "your_email@example.com"

   

4.. Set Up MySQL

1. Download and Install: I downloaded the latest version of MySQL from the official website and installed it on my laptop.
2. Configure MySQL: I configured MySQL by setting the root password and creating a new user.


5. Set Up Google Chrome

1. Download and Install: I downloaded the latest version of Google Chrome from the official website and installed it on my laptop.
2. Configure Chrome: I configured Chrome by setting the default browser and enabling extensions.


5. Development Environments and Virtualization
Chosen Tool: Docker
1. Downloaded the Docker Desktop installer from the Docker Desktop download page, ran the installer and followed the installation prompts.

2. Launch Docker Desktop and complete the setup.


Reflection on Challenges and Solutions
Challenges:
Issue with Python PATH Configuration:
Solution: I reinstalled Python and made sure the "Add Python to PATH" option was checked during installation.
MySQL Configuration Errors:
Solution: I consulted MySQL documentation and forums to properly configure the MySQL server instance.
Docker Installation Issues:
Solution: I ensured Windows features required by Docker (like WSL 2) were enabled and correctly configured.
Conclusion
This document details the comprehensive steps I took to set up my developer environment, including the selection and installation of tools, configurations, and solutions to encountered challenges. The GitHub repository contains a sample project initialized with Git, showcasing the practical application of the setup process.
By following these detailed steps and documenting the process, I was able to create an efficient and productive developer environment suitable for software engineering projects.


Link to my Github Repository Github
