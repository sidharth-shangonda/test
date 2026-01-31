# test
just to learn git and GitHub. 
# clone command
git clone link
 # status 
 git status 
 # git add files  :adds files to commit 
 to add all files:
 git add . 
 or specific file 
 git add <file_name>
 # git commit : used for commit in the locl system 
 git commit -m "reason to add"

 # git push:to to upload local repo content 
 git push origin main 

# add local repo 

# init command:used to create new git hub repo in that working directory 
git init 

git remote add origin link (form the created new repo)
git remote -v (to verify)

git branch (to check branch)

git branch -M main(to rename branch)
git push origin main 


# shortcut if no untrack files to add and commit only single command 
git commit -am "reason"

# Branches 

git branch(to know branch name )

git branch -M main (to rename branch from main to any other)

git checkout -b newbranchName (to create branch)

git checkout branchname (to naviagte )

git branch -d name (to delete branch)

# merging branches

git push --set-upstream origin feature (this will add another branch to github)

git diff <branch name > (to compare the branches ,files and more )

git merge <bracnh name >(merge 2 branches) OR also can be done by pull request 

# pull request : tells other about the changes that have done to your github repo 

git pull origin main(pulls all the content added in github)

# fixking mistakes 

git reset filename(for staged changes i.e if you have added it )
git reset (for all files)

git reset HEAD~1(undo the recent commit) or use 
git log (to get the hash code i.e adress of the commit which you want to undo) 

git reset hashcode (to undo that commit )

git reset --hard hashcode (to delete after all that commit )


 