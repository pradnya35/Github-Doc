# Github-Doc
*  Setting up a Windows Environment
   Goto https://git-scm.com/ and install git for windows
* Use special command line interface "Git Bash" which is easy to work with Git
 * First we need to configure git on our local machine
    * git config --global user.name "TMK Computers"
    * git config --global user.email "computers.tmk@gmail.com"
    * git config core.editor "notepad++ -multiInst -nosession"
    * git config --edit --global
# Creating Git repository on local machine
*  Run below commands 
   * git init DemoApp
   * cd DemoApp
   * ls -la
* Create status of Repository
   * git status
* Create a new file README.md
   * alias notepad="/c/Program\ Files\ \(x86\)/Notepad++/notepad++.exe"
   * notepad README.md
               OR
   *  touch README.md
   * Add some content in README.md file 
   * git add README.md. I have added Hello Shreyansh and save it.
*  Then check status again which shows status that we have an untracked file
   *  git status
*  Track the changes in README.md file with command.
   *  git add README.md
*  If we have multiple new and edited files then we can track them all with a single command
   *  git add .
*  Then check status again which shows status that we have a staged file
   *  git status
*  Now we can commit the file with readable message
   *  git commit -m "Intitial Commit"
   
Creating git repository on GitHub.com
We can create a new repository on github.com with clicking on new New Repository button

Choose a unique name within your account for new repository and add description also

you have 3 options for working with newly created repository

1. create a new repository on the command line
- echo "# sample-repo" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git remote add origin https://github.com/tmk-computers/sample-repo.git
- git push -u origin master

*  Crate clone of repository
   *  $ git clone https://github.com/pradnya35/Demo.git
 2. push an existing repository from the command line
- git remote add origin https://github.com/tmk-computers/sample-repo.git
- git push -u origin master
3. import code from another repository
We can check if local repository is connected with any remote repository
   -git remote -v




