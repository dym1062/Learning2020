# 关于Git和Github 201211
## 先设置用户名和用户邮箱
git config --global user.name 'abcd' 设置用户名  
git config --global user.email 'abc@def.com' 设置邮箱
git config --list 查看设置
## 接着打开一个文件夹，并初始化，使之成为一个仓库
git init
## 分为三个部分：工作区，暂存区和版本库
git add abc.text  
这一步将工作区的文件加入暂存区  
git commit -m '此处是描述' 这一步将暂存区的文件提交到版本库
## 提交到远程库
git push
## 一些别的常见命令
touch abc.txt 建立一个文件
mkdir abc 建立一个空文件夹  
git log  可选参数 --pretty=oneline 查看历史记录，按q退出  
git reflog 查看历史操作  
git reset --hard commit_id 回退
git reset --hard HEAD^ 回退到上一个版本 HEAD^^ HEAD^^^  
git checkout -- abc.txt 将工作区中文件回到上次add或commit的时候  
git reset HEAD abc.tet 可以把暂存区的修改撤销掉，重新放回工作区  


