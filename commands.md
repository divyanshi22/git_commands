## After Installing GIT
 git<br>
 git config --global user. name "write your username here "<br>
 git config --global user. email "write your email here "<br>
 git config --list<br>
 git config user. name<br>
 git config user. email<br>

 
## How to push a project on github
go to that folder and run the following commands<br>
1. git init<br>
2. git add  . <br>
3. git commit -m "commit name"<br>
4. git branch -m main<br>
5. git remote add origin [link of the repo without these brackets]<br>
6. git push -u origin main<br>


## How to push changes that you made in the code? 
git status <br>
git add --all<br>
git commit -m " Label"<br>
git push --all<br>

## How to move back to previous folder? 
command is cd ..<br>
(make sure to put a space after cd then 2 dots)<br>

## How to delete reinitialised git?
Eg:- we type command<br>
git init<br>
and it says reinitialised existing git<br>

So, to delete reinitialised existing git, use the command:-<br>

rm -rf .git<br>

then,<br>

git init<br>


           
