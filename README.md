//1
  git config --global user.name "violafawzy"
  git config --global user.email "violafawzy855@gmail.com"
  git init
  git add .
  git commit -m "add html file"
  git remote add link git@github.com:violafawzy/gitCourse2.git
  git push link master


//2
  git checkout -b dev
  git add dev.html
  git commit -m "add new branch dev"
  git checkout -b test
  git add test.html
  git commit -m "add new branch test"
  git push link dev
  git push link test


//3
  git checkout master
  git rebase dev
  git rebase test
  git push link master


//4
  Locally :  git branch -d BranchName
  Remotely :  git push origin : BranchName



//5
  git stash
  git checkout BranchName


//6
  git tag -a v1.7 -m "version1.7"
  git push link v1.7 


//7
  git tag


//8
  Locally :  git tag -d TagName
  Remotely :  git push link : TagName



//9
![Logo](caramel.jpeg)