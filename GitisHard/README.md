
# Git is Hard

Why is Git so hard - https://news.ycombinator.com/item?id=4200492
Why is Git so hard - https://www.reddit.com/r/git/comments/ojcmxd/why_is_git_so_damm_hard_to_learn/
Tutorial - https://www.atlassian.com/git/tutorials
Git - https://git-scm.com/book/en/v2/Git-Internals-Git-Objects

echo "# CyberLab" >> README.md
git init
git add ---all
git branch -a
git status

git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/rstar13as/CyberLab.git
git push -u origin master


git remote rm origin
git remote -v
------
git remote add origin https://github.com/rstar13as/CyberLab.git
git branch -M main
git push -u origin main
git rm --cached Prod/CyberLabZero -f
git push origin --delete main
git checkout X
git checkout -b new-branch
git commit
git add; git mv; git rm; 
git pull --rebase
git rebase origin/master
git push origin X