# Practice Git and GitHub

This is a sample project for Git/GitHub practicing.

## Instructions

Use any programming language you like

### Fork and contribute to this project

1. Fork this project in your own GitHub account
1. Clone your new project ```git clone <your-project-url>``` 
1. Open the project's folder with some editor or IDE
1. Modify some file(s) or create new ones. Don't worry that you 
may break something.
1. Commit your changes (the first time you may need to 
   set user name and email - see below)
    - ```git add --all```
    - ```git commit -m "some message here"```
    - ```git push origin master```
1. Go to your GitHub project and create a new **Pull Request**. Then 
wait to be notified that your changes are accepted or not.

### Add the forked project as an upstream remote

1. Add the additional remote ```git remote add upstream connection-url```
1. Be sure that you are in the proper branch of your project
```git checkout master```
1. Fetch upstream to see if there are any changed ```git fetch upstream```
1. Merge upstream to get changed and new files ```git merge upstream/master```

### Make a branch

1. Create a new branch ```git branch new-feature```
1. Change to the branch ```git checkout branch```
1. Work on the branch
1. Commit then push the branch if you want ```git push origin new-feature```
1. When ready to merge the branch, first turn to the master branch 
```git checkout master```
1. Then, merge ```git merge new-feature```
   
### Setting user name and email
1. ```git config --global user.name "your-user-name"```
1. ```git config --global user.email your-email```