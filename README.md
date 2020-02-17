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
GIT 
Webstorm
Then, create a Github account using your internet browser. After the Github sign up, start the WebStorm application on your computer. From there, (Assuming that you do not have any project in Webstorm already) you should be greeted with “Welcome to WebStorm ” pop up, where you can see the Logo of WebStorm on the right side of the pop up and there are three options under it: 
Create a New Project
Open
Get from Version Control
Before you get started with Webstorm, there are some settings to go over before it works with the Github account you have created. So, under those three options, there is also an gear icon on the bottom right side of the pop up, where it says “configure.” Click on it or use hot key:
For Window: Ctrl + Alt + S 
For Mac: []
The setting should pop up and you should be able to see a list of categories on the left side:
Click on Version Control drop down menu
Click on Git 
Then, the settings should show up on the right side, where the first options should be “Path to Git executable” and you would need to input that field with the path of the Git.exe file (By default it should be: C:\Program Files\Git\bin\git.exe). 
Click the Test button after you finished putting in the path. A message will show up “Git Executed Successfully” if it is correct.
Click the OK button to exit
Now that Git is ready, the next step is to create a new project, the name of the project will determine what the repository of the Github will be. But we can change that later if needed. In this case, I decided to give the project’s name to be IS117Project
Click on Create a New Project
Choose the location and give it a name instead of leaving it as untitled, so an example would be: C:\Users\yourPcName\Webstorm\IS117Project
Click the Create button at the bottom right side
Then the next step is to create a new file, which in this class, is going to be HTML 5:
Click on the file tab on the top left
Click on New
Click HTML file
Give it a name
Press the Enter key on your keyboard
Here, you will see the file being opened and ready to be edited, we are going to do some editing, start by giving it a title and a heading. After that, we are ready to put the project into Github for version control purpose:
On the top bar, you should see the tab call VCS, click it
Click import into Version Control
Click Share Project on Github ( there should be a Github icon next to the wordings) 
Here you can change the name of the repository or keep it as how you named it locally. 
Click share button
If any above steps are followed correctly and successfully, your project is now on your Github as a repository. 
Go to your Github account using the internet browser
On the left side, you should be able to see the project that you have shared to Github. They should be in the Repositories section.
Since in Github, a project that you created in Webstorm is now called a repository. We can think of both as similar things when both words are mentioned.
Now, it is important to always create a readMe.md file so it would help others that are using the work that you have done. Notice that file of the readme is not .txt but .MD, that is because Github can detect this type of file and put it as a front face of the whole project, so that anyone who visits this project see the readme file. In fact, you are reading it now! So, In Github, we are going to create a readme file:
Click Create new file, the button should be near top left side, next to the long green button
Name it README.MD
Put some text in it, for this tutorial, the text will be Hello World!
Scroll down and click the green Commit new file button
Now Github will navigate you back to the repository’s front face/ main page
You will now see the README.MD section and the words Hello World! In it
Now that we are familiar with basic Github usage, we are going back to Webstorm to make some more changes, commit it and push it into the Github. For this tutorial, we are going to add a paragraph into our web page: 
Go to Webstorm on your computer
Add a paragraph
Click on VCS
Click Git
Click Commit file
It should pop up the options before you commit it
It is required that you put some comment In the Commit Message text field, so that you could document what changes that you have made or what was on your thought/ reason about this commit
Click Commit button, it should be found on the bottom right side
There should be a green message on the bottom left if the commit process was successful. Next, in order to update your progress to Github, you also need to push it to Github:
Click on VCS
Click Git
Click Push, it should have a green arrow icon next to it
The “Push Commits to IS117Project” window should pop up
Click Push button 
It will pop up a possible merge conflict message saying that you need to merge it in order to push it to Github. 
Click merge
After the successful push to the Github, the project in WebStorm also gets updated, Which the ReadME.md file now appears in WebStorm as well.

