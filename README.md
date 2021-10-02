# STM32 Template Repository

Welcome to the github of Ecoillini Supermilage, this is the main git repo where we will all be forking from to build code for the various STM32s on the vehicle.

# Installation Instructions

## Installing EGit Extension in STM32Cubeide
To successfully use this repo while not pushing binaries to the repository, users need to use an Eclipse Plugin built into the stm32cubeide.
To do so, first open the stm32cubeide then at the top menu bar, go to help, and in the drop down menu click on Eclipse Market place
Once there, search for EGit and install EGit - Git Integration for Eclipse extension, and restart the IDE.
In the next section, we will look at actually importing the repository for use in the IDE.

## Importing the repository into STM32Cubeide
To start, first open the IDE, and in the top menu bar click, file and in the drop down menu, click import.
You then are presented with muliple import options; go to the folder that says git, open it, and click on Projects from Git (with Smart Import).
Then, you must click on clone URI.
You will then be shown a dialog asking for information on the repo. Use the information provided by github along with your netid credientials to fill out the menu.
Note: you will have the option to save the password in secure store, though it is currently unknown how they store the passwords.
In the next menu, make sure the master branch or whichever branch you need is selected, then click next.
Choose where you want to store this project on your home system, then click next.
It will then show a summary of what has happened. Click finish, your project should then open up for use.
If it does not, then go to file and import, and in the general folder, click Existing Projects into Workspace.
Select your project directory then click finish. Your project should now be in the project explorer ready for you to open.

## Using git to push changes.
Now that the repo has been installed, it is now time to go over how to push your personal changes to the repository.
Once you have made your changes, right click on the project in project explorer go in the drop down menu to team, and press commit.
This will bring up another menu for you to stage certain files that you want to push to the main repo, use the plus button to move selected files to the staging area, these will be the ones that are pushed to the repository.
After staging the changes, write a committ message describing your changes (if there is a committ format that will be announced later) and hit commit and push.
When asked, push to the appropriate branch, though in the beginning this should be master.
If asked, enter your netid credentials for you to successfully get the authorization to push to github.
If you ever need more advanced pushing menus, you can right click on the project and go to teams and the appropriate menu.
