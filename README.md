# Git 101 
 
 
 ## LAB
 ---
 1.  Create a repo  in github
 2.  Clone the repo
 3.  Create project locally and push it to github

 4. branches
   4.1 Create my branch
   4.2 check out an exiting branch
   4.3 update your branch
   4.4 what is the base branch ?
   4.5 git workflow


5. pull & fecth
6. commits & push



## TOOLS
---

 https://www.sublimemerge.com/
 https://ohmyz.sh/
    ```
      plugins=(git)
    ```

 


## Git Working and Staging Areas 
---
 working area
  B , C

 staging area
 A




## Git Commands 
---
```bash 

 # clone the repo
 git clone git@github.com-darknautic:darknautic/test01.git

# check my remotes
 git remote -v


# set the correct settings 
 git config -l 
 git config --help
 git config --local -l
 git config --local user.email jdjaj@dsad.com
 git config --local user.name ddasda
 git config --local -l

#  set vim 
git config --global core.editor "vim"

# rebase 
git config pull.rebase false

#workign from MacOS to automatilly convert CRLF to LF 
git config --global core.autocrlf input
git config --global core.eol lf


 # create branch 
 git checkout -b "adding-docs"


 git status 
 git add README.md
 git commit -m "primer commit"
 git log 


git push <remote> <branch>


# registra la branch remota como upstream de branch local
git push -U <remote> <branch>

# equivalente a 
git branch --set-upstream-to=origin/<branch> adding-docs



#playing with remotes
git remote add "origin" https://github.com/darknautic/test01.git



```










