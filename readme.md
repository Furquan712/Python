Required dependencies
On completion of this reading, you will be able to identify any required dependencies for your operating system.

Setting up Python on Windows is straightforward and it will install without any required dependencies. On Mac, however, you do need some additional dependencies prior to installing Python.

XCode
To install brew, you need to install Xcode first. Homebrew does not come with its own compiler and it needs Xcode installed for it to work correctly. To install Xcode do the following:

Open a terminal.

Run the following: 

shell xcode-select --install

A popup will appear asking you to confirm the installation. Click on the Install button.

Agree to the license agreement.

brew
Macs do not come with package managers like most Linux distributions. To make up for this an external tool called brew was created. To install brew, do the following:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"