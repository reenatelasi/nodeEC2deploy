# nodeEC2deploy
Install NodeJS and NPM using nvm
Install node version manager (nvm) by typing the following at the command line.

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash

Activate nvm by typing the following at the command line.

. ~/.nvm/nvm.sh

Use nvm to install the latest version of Node.js by typing the following at the command line.

nvm install --lts

nvm install 16

Use nvm to install the latest version of Node.js by typing the following at the command line.

nvm install node

Test that node and npm are installed and running correctly by typing the following at the terminal:

node -v

npm -v

Install Git and clone repository from GitHub
To install git, run below commands in the terminal window:

sudo yum update -y
sudo yum install git -y

Just to verify if system has git installed or not, please run below command in terminal:

git — version

This command will print the git version in the terminal.

Run below command to clone the code repository from Github:

git clone https://github.com/sumant-mishra/node-app.git

This will create a folder with name node-app.

Install dependencies
Now, move to the folder node-app by running below command in the terminal window:

cd node-app

If you check the list of folders using ls command, the current folder structure does not contain the node_modules folder. This folder will be created automatically after installing the dependencies. To install dependencies, run below command in the terminal:

npm install

Start the application
To start the application, run the below command in the terminal:

node index.js
