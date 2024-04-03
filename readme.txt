git init
git add .
git commit -m "commit my git project"

create branch on github

git remote add origin https://github.com/sunchenggaolbf/gitPrj.git
git push -u origin master

默认的就是master


git有三大现象
    1 工作区和暂存区对stash来说都是一样的，放到哪里都可以git stash.
    2 连续stash apply pop的时候，每次都要git add .把回复的内容提交到暂存区。
    3 git stash之后，工作区和暂存区的内容都会消失被保存。(同1)