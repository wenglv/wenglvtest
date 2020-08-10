```
cd learn_git   进入目录
git  init      初始化git创库
ls learn_git   会多次一个.git 目录
git config --global user.name "wenglv"  配置用户名
git config --global user.email "510674127@qq.com"  配置邮箱
git config --global --list  查看用户和邮箱
git status    看git创库状态
git add    git.md                        已暂存到暂存区
gti commit   -m  “提交说明”  git.md      提交到git创库

git remote add wenglv git@github.com:wenglv/wenglvtest.git  连接远程github
git push -u wenglv master     提交到远程github
ssh  -T git@github.com        验证到远程github成功



```
