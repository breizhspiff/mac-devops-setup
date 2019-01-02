# My Mac OS DevOps environment

## Installation

- Install Ansible
- Ensure Apple's command line tools are installed
- Clone this repository to your local drive
- Updating OSX
- Installing Xcode Command Line Tools
- Run `ansible-playbook setup-my-mac.yml -i inventory -K` inside this directory. Enter your account password when prompted.

All commands are listed in [install.sh](install.sh)

    Note: If some Homebrew commands fail, you might need to agree to XCode's license or fix some other Brew issue. Run brew doctor to see if this is the case.
