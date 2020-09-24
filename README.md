# Github Cheatsheet

Follw these steps when you are pushing the code for the first time to your Github repository.

To start using Git from your computer, you’ll need to enter your credentials (user name and email) to identify you as the author of your work. The user name and email should match the ones you’re using on GitLab.

In your shell, add your user name:

` git config --global user.name "your_username" `

And your email address:

` git config --global user.email "your_email_address@example.com" `

# Convert a local directory into a repository

When you have your files in a local folder and want to convert it into a repository, you’ll need to initialize the folder through the git init command. This will instruct Git to begin to track that directory as a repository. To do so, open the terminal on the directory you’d like to convert and run:


` git init `

This command creates a .git folder in your directory that contains Git records and configuration files.

# To add all local changes quickly

``` 
git add . 
```
# Add all changes to commit

` git commit -m "COMMENT TO DESCRIBE THE INTENTION OF THE COMMIT" `

# Send changes to Github
To push all local commits (saved changes) to the remote repository:

`git push <remote> <name-of-branch> `

To push your local commits to the master branch of the origin remote:

`git push origin master`
