# Appendix {-}

## Git commnads {-}


```r
# basic
cd ## change directory
ls ## list files folders
dir ## show files/folders under a directory

# git info
which git
where git
git --version

# config
git config --global user.name "Your Name"
git config --global user.emai. "Your email address"
git config --global init.defaultBranch main
git config --list ## show settings

# add
git add README ## add file README
git add *.R ## add files with extension R
git add . ## all files under the directory

# commit
git commit -m "initial commit"


# checking status
git status

# remove
git rm -f file_name # stopping tracking and delete the file
git rm --cached file_name # stopping tracking but keep the file

# move
git mv file_from file_to
## equivalent to
mv file_from file_to
git rm file_from
git add file_to

# create a new branch and check it out
git checkout -b new_branch_name

# merge
git branch -a
git checkout main
git merge new_branch_name

git branch --merged # finding branches merged
git branch --no-merged # finding branches not merged

# working with remote
git remote ## show remote server name---almost sure is "origin"
git remote -v ## show remote detail
git remote show origin # inspecting remote origin

# push
git push -u origin main
## or
git push -u origin master

git push --set-upstream origin new_local_b ## push a new local branch
git push origin --delete new_local_b ## delete a remote branch
```


## .gitignore example {-}


```r
# ignore all .a files
*.a

# but do track lib.a, even though you're ignoring .a files above
!lib.a

# only ignore the TODO file in the current directory, not subdir/TODO
/TODO

# ignore all files in any directory named build
build/

# ignore doc/notes.txt, but not doc/server/arch.txt
doc/*.txt

# ignore all .pdf files in the doc/ directory and any of its subdirectories
doc/**/*.pdf
```



