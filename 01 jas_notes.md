#git & github notes

git clone "our_url with out quotes"

git init

git status

git add .

git commit -m "version name" -m "description"

git config --global user.name "user_name"

git config --global user.email "user_email"

git remote add origin "url"

git push -u origin master


for a modified file -> git commit -am "version_name and message"

To check number of commits -> git rev-list --count master

To check the difference between modified file and previous file use command
-> git diff

for undo something  ->git reset HEAD~1

To switch branches            -> git checkout

To create a new branch        -> git checkout -b branch_name

to delete an existing branch  -> git branch -d branch_name
