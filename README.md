# IS117_Spring2020

GIT - PC based version control system

GITHUB - Server side version control system

Repository - In Github, it is a folder that containts all of files and source codes from a project.

Clone - A command that downloads an existing Git repository to a computer's local drive.

Commit - To make permanent changes

Push - Sends the commited changes to the specific repository in Github.

Pull - Takes changes from Github's specific repository and merges it into the local repository on the computer.

Branch - A version of a work in progress of the project, where it allows to have mutiple branches to serve as a mean fix bugs, exepriment and develop new feature withouth messing up the master branch. 

Merge - Combine and intergrate both branches of the project into a single branch.

Merge Conflict - An event that occurs when there are cometing line changes. 

Fetch - A command that downloads commits, files, and refs from remote repository (Github) to the computer's local drive.

Remote - A common repository in Git that all of the team mebers use to exchange their changes. 

===============================================================================
Before getting into the process with Github, First, there are some software to be installed into your computer: 
1. GIT 
2. Webstorm

Then, create a Github account using your internet browser. After the Github sign up, start the WebStorm application on your computer. From there, (Assuming that you do not have any project in Webstorm already) you should be greeted with “Welcome to WebStorm ” pop up, where you can see the Logo of WebStorm on the right side of the pop up and there are three options under it: 

1. Create a New Project
2. Open
3. Get from Version Control

Before you get started with Webstorm, there are some settings to go over before it works with the Github account you have created. So, under those three options, there is also an gear icon on the bottom right side of the pop up, where it says “configure.” Click on it or use hot key:

    1. For Window: Ctrl + Alt + S 

The setting should pop up and you should be able to see a list of categories on the left side:
    1. Click on Version Control drop down menu
    2. Click on Git 
    3. Then, the settings should show up on the right side, where the first options should be “Path to Git executable” and you would need to input that field with the path of the Git.exe file (By default it should be: C:\Program Files\Git\bin\git.exe)
    4. Click the Test button after you finished putting in the path. A message will show up “Git Executed Successfully” if it is correct.
    5. Click the OK button to exit

Now that Git is ready, the next step is to create a new project, the name of the project will determine what the repository of the Github will be. But we can change that later if needed. In this case, I decided to give the project’s name to be IS117Project

1. Click on Create a New Project
    2. Choose the location and give it a name instead of leaving it as untitled, so an example would be:C:\Users\yourPcName\Webstorm\IS117Project
3. Click the Create button at the bottom right side
Then the next step is to create a new file, which in this class, is going to be HTML 5:
    1. Click on the file tab on the top left
    2. Click on New
    3. Click HTML file
    4. Give it a name
    5. Press the Enter key on your keyboard

Here, you will see the file being opened and ready to be edited, we are going to do some editing, start by giving it a title and a heading. After that, we are ready to put the project into Github for version control purpose:
    1. On the top bar, you should see the tab call VCS, click it
    2. Click import into Version Control

Reference: 
Hendela, Arthur H. (2014) Introduction to Github and Webstorm
Hendela, Arthur H. (2020) Additional Instruction on Creating a Git and Github repository
