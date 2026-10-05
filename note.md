# version
       
 Version control is a system that records chages to a file or set of files over time so that you can recall specific versions later. It allows multiple people to work on a project simultaneously, tracks changes, and help manage conflicts when merging contribtions from different collaborators. popular version control systems iclude Git subverstion (SVN) and mercurial. 

### setup
To set up version control for your project, follow these steps:

1. **Install a version conrol system**: choose a version control system (e.g git) and install it on your machine.
2. **initialize a repository**: Navigate to your project directory and initialize a new repository using the command 'git init' (for git).
3. **Add Files**": Add the files you want to track using 'git add <file>' or git add' to add all files.
4. **commit changes**: commit your changes with a discriptive message using 'git commit -m "your commit message".
5. **create a remote respository**: if you want to collaborate with others create a remote repository on platforma like github gitlab or bitbucket.
6. **push changes**: push your local commits to the remote repository using 'git push origin main' (replace 'main'with your brach name if different). 

### Branching
Branching allows you to create separate lines of development within your project.This is useful for working on new features or bug fixes without affecting the mian codebase.

To create a new branch, use the command 'git branch <brach-name>,' and switch to using 'git checkout' <branch-name>' or you can create and switch to a new branch in one command using 'git checkout -b <branch-name>'.

After making changes, you can merge the branch back into the main branch using 'git merage <branch-name>'.