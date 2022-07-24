# SMS(School Management System)
1. If you don't have Git installed, see this article on how to set it up.
2. Open up a Windows command prompt.
3. Change into the directory where your source code is located in the command prompt.
4. First, create a new repository in this directory git init. This will say "Initialized empty git repository in ....git" (... is the path).
5. Now you need to tell Git about your files by adding them to your repository. Do this with git add filename. If you want to add all your files, you can  git add .
6. Now that you have added your files and made your changes, you need to commit your changes so Git can track them. Type git commit -m "adding files". -m lets you add the commit message in line.
So far, the above steps is what you would do even if you were not using GitHub. They are the normal steps to start a Git repository. Remember that Git is distributed (decentralized), meaning you don't need to have a "central server" (or even a network connection), to use Git.
Now you want to push the changes to your Git repository hosted with GitHub. You do this by telling Git to add a remote location, and you do that with this command:
git remote add origin https://github.com/yourusername/your-repo-name.git
*Note: your-repo-name should be created in GitHub before you do a git remote add origin ...
Once you have done that, Git now knows about your remote repository. You can then tell it to push (which is "upload") your committed files:
git push -u origin master

