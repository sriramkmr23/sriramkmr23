//To add the User Name
git config --global user.name Ram

//To add the enmail address
git config --global user.email sriram.kumar@navitas.com

//Inistialize the file
git init 

//Show hidden files
ls -lart

//Add the file in staging mode
git add index.html 

//To create the html files in folder
touch about.html

//Check the file status
git status 

//Add all files in statging area
Git add -A 

//Move File to Working tree
git commit -m "added some html content" 

//Backup last updaded html files for single file
git checkout services.html 

//Match last commint of all the modified files
git checkout -f

//Show who has modified the files
git log 

//show last 2 commit with author details
git log -p -2 

//exit back to the terminal mode
q

//its comapare working directory files to staging area file.  If we change in tag show in details
git diff 

//Skip staging area and fixed the error
git commit -a -m  "skip staging area and fixed error"

//: show list of the files
ls 

//Remove file from the staging area and also from the working tree
git rm about.html 

//remove only from the working roots not from the staging area 
git rm --cached index.htm 

// Sort modified status
git status -s


//Git Ignore
     
.gitignore
  mylogs.log (ignore single mylogs.log files)
  * mylogs.log(ignore all  mylogs.log files)
  * mylogs.log/(ignore from directory)


//Branch Command (Which is used to coppy the main branch)
  git branch feature1 : Create Branch
  git checkout feature1 : Switch to branch
  git checkout -b headerfile : Create branck and swithch direct to that branch


//Github connect with local laptop
git remote and origin https://github.com/sriramkmr23/ram-repository.git (Connect remote repository to local repository)
git remote -v ( show the push and fetch url)

//For push data.............
git push origin master

// Key Details
$ ssh-keygen -t ed25519 -C "your_email@example.com"
eval "$(ssh-agent -s)"
$ ssh-add ~/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub : To get the ssh key and add this to account
git remote set-url origin git@github.com:sriramkmr23/sriramkmr23.git
git push -u origin master



