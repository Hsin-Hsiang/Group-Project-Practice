# Group-Project-Practice
A project for practice using git during group projects, with this repository being the project manager.

## Sources
This repo follows the method written by sir Andrew Matheny's [This Medium Post](https://medium.com/@androidmatheny/using-git-and-github-on-group-projects-d636be2cdd4d).
All credits goes to him.

## Basic Consepts
The project will be managed as the folloing image:
![image](https://user-images.githubusercontent.com/41797532/113405737-dcb6fc80-93dc-11eb-93bd-f7005ce890d4.png)

with you acting as the **group member**, forking and sending pull request to this repositiory.

## Steps
### First of all, setup git.
#### If you are on Linux:
Use the command `sudo apt-get install git` to install. Type `git --version` to confirm.
#### If you are on Windows:
Get [GitBash](https://gitforwindows.org/) and install. After install, you should be able to open a command prompt through the .exe file.

### As the group member:
1. Click **Fork** on the [main repositiory](https://github.com/Uduru0522/Group-Project-Practice). 
> Now you should have your own fork.
2. Clone the forked repositioy with `git clone https://github.com/ <Your GitHub ID> /Group-Project-Practice.git`.
> Now you should have the forked repository on your local machine. Use the command `ls` to confirm.
3. Use command `git remote -v`. You should see a remote named `origin`. 
4. Use command `git remote add upstream https://github.com/Uduru0522/Group-Project-Practice.git`
> This is to set connection to the **main project**. This way you can pull updates on the main repo. (The arrow labled "C")\
5. Make your changes and commit. The instructions on properly making change on projects are at below.
6. Run `git push origin master` to push changes to *your fork*. 
> You should be able to see the updates on `https://github.com/ <Your GitHub ID> /Group-Project-Practice`
7. At the website, click "Send Pull Request". After the project manager merges, you can see the changes on main repo.
