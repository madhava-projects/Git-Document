Git(VCS)

Git is a version control system used for tracking changes in computer files. It is generally used for source code management in software development.
•	Git is used to tracking changes in the source code
•	The distributed version control tool is used for source code management
•	It allows multiple developers to work together
•	It supports non-linear development through its thousands of parallel branches

Features of Git

•	Tracks history
•	Free and open source
•	Supports non-linear development
•	Creates backups
•	Scalable
•	Supports collaboration
•	Branching is easier
•	Distributed development

Git Workflow

The Git workflow is divided into three states:
•	Working directory - Modify files in your working directory
•	Staging area (Index) - Stage the files and add snapshots of them to your staging area
•	Git directory (Repository) - Perform a commit that stores the snapshots permanently to your Git directory. Checkout any existing versions, make changes, stage them and commit.
 
Branch in Git

Branch in Git is used to keep your changes until they are ready. You can do your work on a branch while the main branch (master) remains stable. After you are done with your work, you can merge it with the main office.
 

Installing Git for Windows

1. Download Git for Windows:  https://git-scm.com/downloads
2. Click the download link for Windows 64 bit and allow the download to complete.
3. Browse to the download location .Double-click the file to extract and launch the installer. Click Run and Yes on the User Account Control dialog that opens.
4. Review the GNU General Public License, and when you’re ready to install, click Next.
5. The installer will ask you for an installation location. Leave the default, unless you have reason to change it, and click Next.
6. A component selection screen will appear. Leave the defaults unless you have a specific need to change them and click Next.
7. The installer will offer to create a start menu folder. Simply click Next.
8. Select a text editor you’d like to use with Git. Use the drop-down menu to select Visual Studio Code (or whichever text editor you prefer) and click Next.
9. The next step allows you to choose a different name for your initial branch. The default is 'master.' Unless you're working in a team that requires a different name, leave the default option and click Next.
10. This installation step allows you to change the PATH environment. The PATH is the default set of directories included when you run a command from the command line. Leave this on the middle (recommended) selection and click Next.
11. The installer now asks which SSL client you want Git to use. Git already comes with its own SSL client, so if you don't need a specific one, leave the default option and click Next continue Next..
12. Depending on the version of Git you’re installing, it may offer to install experimental features. At the time this article was written, the options to include support for pseudo controls and a built-in file system monitor were offered. Unless you are feeling adventurous, leave them unchecked and click Install.
13. Once the installation is complete, tick the boxes to view the Release Notes or Launch Git Bash, then click Finish.

Git Commands:
1. Know the version of Git: git --version
2. A directory into an empty Git repository:  git init
3. add all files to the stagging area: git add .
4. record changesmade :git commit -m 'madhava-projects'
5. current state of repository : git status
6. assign settings user name to git: git config --global user.name "madhava-projects"
7. assign settings user email to git:git config --global user.email "madhavaraomaganti@gmail.com"
8. create and checkout current branchs:git branch project1      git branch
9. swithcing branchs :git checkout project1
10. integrate branchs together: git merge project1
11. connects a local repository with a remote repository:git remote add origin https://github.com/madhava-projects/Git-Document.git
12. create a local working copy of an existing remote repository: git clone https://github.com/madhava-projects/Git-Document.git
13. commits history from local to git hub: git pull origin master: git pull origin master
14. commits history from remote git hub to local: git push origin master
15. to save changes made when are not in a state to commit them to a repository:git stash apply
16. context & history for a repository: git log
17. rollback to the previous state: git revert mychange
18. 


