# github-tutorial
This is where I store my examples about github
 
## Make a directory a Git repository

$ git init .

## Check the status of your repository:

$ git status

## Add the file.txt to the Git staging area

$ git add file.txt

## Commit the file to the Git repository:

$ git commit -m "Adding file"

## Look at the Git logs:

$ git log

## push to GitHub!

### First you have to create a remote repository. 
Go to GitHub and create or login to your account.
At the top right of any Github page, there is a ‘+’ icon. Click that, then select ‘New Repository’.
Name your repository python_tutorial. It is best practice for your local project and GitHub repository to share a name.
And click “Create Repository”
Copy the link to your GitHub repository.
Copy the link in the input right beneath the title, it should look something like this:
https://github.com/<user_name>/<repo>.git

### set your remote repository, in your project terminal type:
$ git remote add origin <remote repository URL>

Note
Your remote repository URL is the link you copied in step 5!
And verify your remote repository:

$ git remote -v
And finally push your project to GitHub:

$ git push origin main
