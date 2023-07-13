Day 3 Assignment on Git

Initialize a local repository and name the base folder as ‘basic_training’.
Ans:- $mkdir basic_training
	$Git init
Set your local configs (Name and Email).
Ans:- $git config --global user.name "Albin Thomas" 
$git config --global user.email athomas@deqode.com
Create a file named README.md inside this folder.
Ans:- $ touch README.md
Add the following content to this file. Basic Training Solution Submissions
Ans:- $echo ‘Basic Training Solution Submissions’>README.txt
Create a fresh commit in the master branch named ‘Initial Commit’ containing
only the created README.md file.
Ans:- $git add README.md
	$git commit -m ‘Initial Commit’
You need to create a repository on Gitlab ‘Basic_training’.
Ans:- Done
Set remote on your local repository to the new repository on Gitlab.
Ans:-$ git remote add origin git@github.com:Albin-Deqode/basic_training.git
Add your buddies(primary and secondary) and mentors to your repository as a ‘Maintainer’
Ans :- Done
Create a branch from the master named ‘assignment-X’, where X indicates the
assignment number in the order that you received in daily Emails.
Ans:- $ git checkout -b assignment-3

