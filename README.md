# This is my end to end project 

install Git bash from gitscm website
use command "git init" in git bash terminal 

need to configure Git with login credencials
command used are 
git config --global user.email "you@eaxample.com"
git config --global user.name "username"

after login git account is linked current project all the data can be stored in the git 

git add filename.txt
git add .   # this 2 statements execution can be done using vs code souce control tab in left side 

can use below command in git bash
git commit -m "this is my first commit"

TO use VScode we can tansfers the files to git 
by going to source control tab in left side 
we can observe the file name at the corner of file name. if we drag the curser on to the file name we can observe the + icon to change the state. after clicking that we can commit the file git by writting the text. we will get a option to publish the file on git after accepting it file moves to github repo.

After file creation right corner of the file name we can observe some Characters shown below
U =Untracked  -- New file created
A= index added --- after clicking on + icon file moves to stage change so we can observe this.
M= Modified --  after file saved to git then if we modify in the file we can observe this.

Now we can create a file on the git (It is a important step)
After going to current repo on the git we have to + icon just beside code button if we click on it we can select the option to create new file. 
Then provide a name to it . as .gitignore  then judt below that we have a option the select the template. Language wise we can select the template we can select the python so template will be loaded.
then commit the changes. file will bec created. 
Note: select the option to create the file in the main branch.

Now, will create one more file for License selction (License file mainly used for production purpose. License file provide some permission and limitations)
create a new file name it as LICENSE the select the template for License. and commit the changes.

by using the bash script also we can pull the changes from the git repo using " git pull" command in bash


Will create new file name init.setup for initialising the setup automatically using shell scipt
then will create a requirements.txt file  where all required python libraries are available.





