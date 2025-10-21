# __How to create GitHub Repositories & and Add Commits__
## 1. Setting your directory
### Create your file folder, perferably in an easy filesystem, like on your desktop. Go into your folder and click on the filepath link bar, now erase the current filepath and in its place, type "cmd". This will open the command prompt in your folder's filepath.

## 2.  Initialise Git in your folder
### Given that you have Git installed (if you don't, here's the [link](https://git-scm.com/downloads)), type in your newly opened command prompt "git init" to initialise Git within your folder. To check that it has sucessfully initialised, on your file explorer, go to the "view" tab and check the "View Hidden Items" box. You should now see a .git folder appear in your folder.

1. ### Add your account
#### Type (or copy/paste) the following command into your command prompt:
#### '*git config --global --edit*'
#### This will open a text document which has your account details with hashtags before them. Remove the hashtags from just your details, save the document and close it.

2. ### Create a document
#### You can copy documents that you already made, or create a new text document inside of your folder. When you have added your file to the folder, copy its name, type in the following command and paste the name into the command:
#### '*git add (file.format)*'
#### Replace the brackets with your file name. You have just started the process of adding your file to your git repository

3. ### Committing your change
#### After making a change to your git repo, like adding a file, type the following command to commit the change and to name your commit:
#### '*git commit -m "(Name of Commit)"*'
#### Replace the brackets with the name of your commit. Your changes have been committed, you will be able to see the name of your commit beside your file name

4. ### Creating a Branch
#### The following command will create a branch off your main git repo for your new file:
#### '*git branch -M main*' 

5. ### Adding your remote origin
#### The next command will add a remote origin for your git files to be pushed to. Currently you have been only working with an offline git repo, but now you will be able to push your files onto your internet hosted git repo:
#### '*git remote add origin (https//GitHub.com/user's_name/repo_name.git)*'
#### Replace the brackets with the URL for your GitHub repository. You can almost put your files on your GitHub repository.

6. ### Pushing your files to your GitHub repo
#### This final command will send your files to your online GitHub repository. 
#### '*git push -u origin main*'
#### Now your files should appear on your GitHub page. You can download access them from the internet now and download them remotely.

# HI EVERYONE! THIS WAS EDITED ON GITHUB ON THEIR WEBSITE! 
