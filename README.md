# WebApp
Web applications using JavaScript

For this project we are going to develope a Web Application using JavaScript for the front end as well with Java for the 
backend functionality.

Commands: 

clone repo to local: git clone <name_of_project> 

Adding your name to this README.md file

- click on README file - open file 

- put your name on the file then and then save file (command s) 

- adding from local to remote repo 

- command; git status 

- this will allow you to see the files that have been changed (marked red)

- command: git add <name of file> that you choose to add to the remote repo also if there is a lot of file changes that come out as red 
remember to do 

-command: git add . 
this will allow to add all of the file changes withouth having to do the prev command one by one, remember this is add with a period at the end 

- command: git commit -m "<describe your changes>" this will let your team mates know what changes you have applied to the file

- command: git push 

- this will allow for all of the pushes to be submitted to remote repo 


evaluating these changes, remember to be aware of your master and dev branch to be currently updated, we have the master 
branch which will be the branch which should always be functioning it has to be as bugged free as possible, nothing should
be pushed or commited to the master branch without any pull request approval. We in order to merge to master branch remember 
that we will do a pull request, further instructions will be covered. Dev branch will be a branch that will have team members 
worked merged into one in order for it to function, this will be the branch dummie where everything can be dubugged or even 
have crashes, this branch is not considered the final product but close to it from master.

update your master

- command: git checkout master 

- command: git fetch 

- command: git pull

update your dev 

- command: git checkout dev 

- command: git fetch 

- command: git pull


Remember if you want to work on the project you once you create your branch remember to always be under the Dev branch 
so in order to branch off of dev use 

command: git checkout dev 

command: git pull 

command: git fetch 

command: git checkout -b [name_of_your_new_branch]

command: git push origin [name_of_your_new_branch]



Developers: 

Hernan 