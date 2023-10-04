# A02

How to set up github and webstorm with a remote repository

Step 1: Create a new github repository and name it whatever you want.

Step 2: Grab the github 'url' seen on the top right of the directory window - for SSH users, it is necessary for your machine to have an SSH key, while for HTTPs users, you can use your login credentials (or token)

Step 3: Go into GitBash (https://git-scm.com/downloads) or the Linux Terminal, navigate into a new folder of your choice, and type 'git clone <url>'. This will download the repository you created onto your computer. The folder you chose for
your github repository is now considered your 'working directory' within this tutorial.

Step 4: Your project should typically have an automatically generated README.md - if it doesn't, you can type one within github or make one in the command line.

Step 6: Too add files to your local repository, drop them into the working directory, and then follow the steps to push them to your branch

Step 7: to save your changes, within the command line in your working directory type in a a few commands:
* git add .                    #adds all files which were modified within your working directory to a queue
* git commit -m "comment here" #commits all files to the queue as is
* git push --all #pushes everything to the working branch online"

Step 8: to integrate webstorm, simply make a new project within your working directory and then commit the entire project to your repository. Please make sure to test if you can clone your repo from any machine and work from there.

Addendum

* To Pull (or update your remote repository), type git --pull all and it will automatically update your local repository
* To solve merge conflicts (When merging two branches in your remote), do the following
  * Check the current conflicts and resolve them one by one. It is important to make a mental note of each change your make and outline a general plan of what needs to be changed
  * Make sure the branch you are merging into is NOT write protected.
* Fetching a branch can be used to switch to a branch, while cloning simply clones the current branch you are on.

Definitions:

* Branch: An individual workspace with a collection of source-controlled files within a repository
* Clone: To download and synchonize the contents of a repository to a local branch
* Commit: To add pending changes to a branch
* Fetch: To switch or copy the contents of another branch to your hard disk
* GIT: A version of source control popular since 2005, used within many software development enterprises
* Github: A git-based website which easily maintains repositories of code which people can easily view and access
* Merge: The act of merging two branches into one, or to copy the contents of one branch to another
* Merge Conflict: When the files of two branches do not match each other. This can typically be due to a series of files not coinciding correctly
* Push: To update a branch on the remote repository
* Pull: To update a branch on the local repository
* Remote: A repository located on a computer network (github)
* Repository: A collection of version-controlled source files for a project






