dev-machine-setup
=================

This repo contains Cloudspace's setup scripts to configure new OS X dev machines.  The script will install/upgrade Xcode command line tools, virtualbox, packer, git, etc.

## Configuring a new computer

0. Install XCode from the Mac App Store; and start Xcode so you can accept the terms & conditions before moving on
1. Run the following script in terminal on your computer:
`bash <(curl -s https://raw.githubusercontent.com/cloudspace-devops/dev-machine-setup/master/osx-dev-machine-setup.sh)`
2. When prompted, select "Install" to get the command line developer tools.  After the install completes, dismiss the dialogue and press [return] in terminal.
3. Enter your system password when prompted to install Brew
4. Enter your full name and password for git when prompted.
5. If prompted, enter your system password to create a /srv folder for development.
6. If prompted, press enter to use the defaults three times to generate your id_rsa key.
