Task 1
Installation instruction on an RPM-Based Linux System
1. Overview
The installation process involves running a script and then installing a required package of a specific version.
2.  Definitions
Repository – а storage location containing software packages and metadata for use with package managers like dnf or yum.


Package – а compressed archive file (with the .rpm extension) that includes software binaries and configuration data.


Version – а specific release of a package, used to maintain compatibility or apply updates.
3. Installation Steps
3.1 Download the script from the repository.
3.2 Run the installation script and set up the environment and dependencies:
sh install
3.3 Install the required package and version using your package manager:


The list of questions
Where is the repository stored? Is there a link for it?
What is the command for the installation of the package and version?
What is the package name and is there a certain version that should be installed?
How to verify that the correct version and package were installed?
What should the user do if the installation fails?


Task 2
Uninstalling the Package
If you no longer need the package you can uninstall it. Use the following command in the terminal:
yum remove mypackage
This command will uninstall the package and delete the files that were installed with it.
If you are prompted for confirmation, type y and press Enter to proceed.



