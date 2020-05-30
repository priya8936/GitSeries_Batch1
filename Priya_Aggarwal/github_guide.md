# Complete guide about git and GitHub.📔
------------------------------------------------------------------------------
**What exactly do u mean by Git and Github?**
 >**Git** is a popular control system which is installed and it maintains all your 
local system and gives you a self-contained record if your ongoing programming 
versions. Git is easy to learn and has a tiny footprint with lightning-fast 
performance.<br> It outclasses SCM tools like Subversion, CVS, Perforce, and ClearCase 
with features like cheap local branching, convenient staging areas, and 
multiple workflows. Git is written in CC, Perl, Tcl, Python. The original author is
Linus Torvalds. The best part about Git is that you don't need an internet connection to 
access it and it is free of cost and easy to use. <br>
GitHub is designed as a Gut repository hosting service. Git repository hosting is 
an online database that allows you to keep track of your work and shares your 
Git projects outside the local server. It is popular for open source projects. 
If the server is failed then the data is not lost since it is saved in your 
local repository. The parent organization of GitHub is Microsoft Corporations.
It was founded in 2008 and the CEO of GitHub is Nat Friedman. Github is written 
in Ruby. Github has a total of 40 million users by Aug 2019. Founder of GitHub is
Tom Preston-Werner, P.J Hyett, Chris Wanstranth, Scott Chacon.

**Why Github is so popular in most of the projects?**
>The Largest shared repository- Pushing the project to a shared, public repository
makes it instantly discoverable for those 28M users.
Easy Version Control- It tracks all the changes made to your code and who makes them.
Immensely Powerful Community-itHub is an open-source platform, and the community is
that fills it up.<br>
Secure Cloud storage-The platforms protect all your data for you: protects code branches, 
verifies commit signing, controls access. <br>
### Some other platforms which can be used instead of GitHub are as follows:-
>a.GitLab<br>
b.Google cloud source repositories <br>
c.AWS Code commits <br>
d.Apache Allura <br>

**How git workflow works? What are the different stages of a git 
the project as commit, add?**<br>
>Git workflow has a total of four major stages as mentioned below:-<br>
>1. Working directory - Workspace.<br>
>2. Index ie stage<br>
>3. Local Repository ie Head<br>
>4. Remote Repository<br>
GitHub is essential, a pretty representation of the work of many 
software all together called 'Git'. Git works by keeping track of all the changes that 
you do to any files within a particular folder. This is essentially, no 
different than the View Previous Versions of this file feature on many 
operating systems but come with added benefits and so complexities too. 
Github is simply skin or a representation of the actual stuff - Git.
There is one central repository. 
Each developer clones the repo,
works locally on the code,
Modifies and makes the changes as required
Commit the changes using command commit -a with changes
and push it to the central repository 
for other developers to pull and use in their work.

**Forking**
>Forking means that you have a copy of that project in which you want to work. It is 
simply creating a personal copy to edit it without changing the final content. We create
a copy of the main repository of a project source code to our GitHub profile. 
In this, we can do any changes without affecting the main source of the project. 
Fork repository makes a connection between our fork and the original repository and us
can go back to the original project using a pull request. 
Forking can be done in two simple steps.
>>1. Open the project repository of the person you want to work in.
>>2. On the top right corner, you just have to click on Fork.

**Cloning**
>After you are done with a fork and you have your copy of the original project we will clone it.
Cloning means when you create a new repository on your remote location where the project is stored.
We have to sink the local and remote locations of the project.
We do clone to make our repository on our local computer. 
We cannot pull the changes from the original repository when cloning. 
>>step1. Under fork click on clone and download.<br>
>>step2. Copy the URL<br>
>>step3. Open Gitbash<br>
>>step4. Use the command:-<br>
>>git clone url_copied <br>
step5 Enter<br>
Now you are connected to the location of the project.
After cloning is done we will make our project and store it in a folder.
Now you have to make a PR. PR stands for the pull request. To understand PR first we have to
understand the concept of branching.

**Branching**<br>
>When we create a repository, then the main linear list of 
commits is on the master branch. We can makes changes in master as well 
as in a new branch. All the branches are independent of each other. 
After editing we can commit the changes in the branch directly or create 
a new branch. <br>

**Steps to create a branch**<br>
>1. git remote (This will give you the remote location ie origin)<br>
>2. git remote add upstream url_copied (This will add a new remote location name upstream)<br>
>3. git add . (This command lets you add the work to have done)<br>
>4. git commit -m "message" (This will allow you to commit changes you have made)<br>
>5. git pull upstream master (This will pull location from master)<br>
>6. git checkout -b branch_name (This command helps you to create a new branch)<br>
>>After the branch s made you will again add and commit changes you have made.<br>
>>Once the branch is made we will push our work into the repository and then request for a PR<br>

**This can be done in three simple steps:-**<br>
>1. git push origin master<br>
>2. git checkout branch_name (This will et you to the branch you have created above)<br>
>3. git push origin branch_name (You have finally pushed your branch and project)<br>

>>If you want to contribute in the existing repository then fork that repository first and 
do some changes in the repository's any section even if you change documentation of 
that repository's code and you think it should be in the master repository of the main repository 
then a pull request it to the main repository so that master can see and made changes to the 
repository.<br>
It lets others know about the changes we have pushed to a branch in 
a repository of GitHub. Once the pull request is open we can discuss 
and review it before the changes are merged into the main brach. <br>

**Steps for pull request:-**<br>
>1. Go to the main page of your repository<br>
>2. Choose the branch you have made successfully<br>
>3. In the right, you have an option to make a new pull request, click on it.<br>
>4. Type a title and description for your pull request.<br>
>5. To create a pull request that is ready for review, click Create Pull Request.<br>

**Issue**<br>
Issues can be used to keep track of bugs or other requests.<br>
Steps to create an issue:-<br>
>1. Go to your main repository<br>
>2. Click issue<br>
>3. Click new issue <br>
>4. Click get started<br>
>5. Write a title and description of your issue.<br>
>6. Add labels, assign to someone, and click Submit new issue.<br>

>>After the PR is accepted we have to finally do one last step ie called merge.
We have a merge conflict which when git it is unable to automatically resolve the differences 
in the code by itself between two commits. When there is a conflict git 
doesn’t know which code to keep and which to discard. For eg if there are 
conflicting changes on the same line or some file is deleted on one branch 
but not on another. Merge conflict can only be resolved by the developer. 
These conflict usually happens when working in a team environment. <br>

**The command for the merge is**

**"git merge branch_name"**

>a. Git fails to start the merge when there are changes in the working directory 
or staging area of the current project.
>b. Git fails during merge - conflict in the current local branch and branch being
merged. <br>
### I hope this guide will direct you easily and you can have a look at my GitHub

**I am sharing the link below:-<br>
https://github.com/priya8936**<br>

### Enjoy..!! 

### Github is fun to use and I would like to thank my mentors in guided me through this whole process.


### Thank you

### Regards

### Priya Aggarwal

