Installed NVM for WINDOWS

This is the Node Version Manager.
It manages the current version of Node and npm that's running on your computer

Using NVM, I installed Node and npm

to check your current version of node use:
node -v in your powershell terminal

to check all version available use:
nvm list available

to switch the version of node that you want to run on your computer use:
nvm use "node version"    ---- instead of node version but the number of the version you actually want such as:

nvm use 20.12.2

Now that NVM and Node is installed you can use npm and npx for node projects that use react or anything else based on Node

To create a new Next.JS app:
* go into vscode
* open up a new empty folder
* open a new terminal
* run: npx create-next-app@latest
* Let it install and answer the prompts it gives you

Once its installed navigate into the new project folder.
After that you're good to develop

Make sure that your project is connected to a github repo. 
This isn't necessary tho if you dont want the project to be public