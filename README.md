# GitTest

####create a new branch
git checkout -b create-newbranch

####check current branch
git branch

git status

git add .

git commit -m "message"

####switch to master branch
git checkout master

####merge create-newbranch to master branch
git merge create-newbranch

####delete branch create-newbranch
git branch -d create-newbranch

git push

#### set upstream
git push --set-upstream origin create-newbranch

#### clone the specific branch
git clone -b create-newbranch https://github.com/GreatEric/GitTest.git




