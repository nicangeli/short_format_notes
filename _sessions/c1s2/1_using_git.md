---
title:  "Intro to Git"
---

![Basic git](/assets/basic_git.png)

Git is a version control system. It allows you to keep the entire history of your code, and makes it easy to share and collaborate with others.

### Setting up a git repo

Git works on a folder level. To set up a folder to work with git you need to open up the Sourcetree app and select `File > New / Clone`. You then need to select the Create Repository tab from the top menu. In the Desitnation Path browse to the folder that you want to control with Git.  


### Excluding some files

There are some other hidden files (e.g. those used by your operating system) that you don't want to be version controlled. An example of these is the `.DS_Store` file on macs. We'll talk more about this later - for now we'll just quickly exclude them from our repository.

To do this you need to change the settings on your repository.

This won't work with Sourcetree. If you try and do this email Nick.

1. Open the settings tab of your repository.
2. Add `.DS_Store` on the first line of the 'Ignored files' section, and press 'Save Changes'.

If you're on Windows you don't need to worry about this.

### Committing files to the repository

Suppose we've now created a file called `index.html` in the folder. It's in the folder but currently isn't being tracked by git. 

Adding files to a git repository is actually a two-stage process: you have to **add** them and then **commit** them. This is useful when you get more advanced, but we'll usually do those things together for the time being. 


{% exercise %}
1. Create a new folder that will be home to your personal project that you'll use throughout this course. (Or skip this if you already have something you want to use)
2. Set up this folder as a git repository: open up Sourcetree, select `File > New/Clone ...` and select your folder in the destination path.
3. Add your files to the staging area one by one using the Add button. The files should move from the working tree (bottom) panel to the staged panel (top).
4. Commit your work to the repository using the Commit button. Type a commit message and hit commit. 
6. Make some change to index.html (in Sublime Text, or another file if you don't have an index.html file)        
7. Go back to Sourcetree. Select and commit your changes, with a 'Commit message' describing what you did.
{% endexercise %}