## Story Node Setup Script
This script automates the installation and configuration of a Story Node. It performs the following tasks:

- Installs necessary dependencies such as curl, git, make, and Go.
- Installs the required version of Go programming language.
- Clones and builds the story-geth and story repositories from source.
- Configures the node based on user input as either an RPC Node or a Validator Node.
- Sets up systemd service files for story-geth and story for easy management.
- Provides instructions for applying snapshots and starting the services to complete the node setup.

## Usage 
```bash
wget https://raw.githubusercontent.com/neulerfzco/story-one-liner/refs/heads/main/node.sh
chmod +x node.sh 
./node.sh
```