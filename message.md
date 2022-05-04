# zherui

```
cd ~/.ssh

ls						//查看是否存在 id_rsa 和 id_rsa.pub文件

ssh-keygen -t rsa -C "邮箱@qq.com"

cat id_rsa.pub		   //查看ssh公钥

ssh -T git@github.com  //运行结果出现类似如下 successfully
```

```
echo "# 文件内容--标题" >> README.md
git init
git add README.md
git commit -m 'first commit'
git branch -M 分支名   //重命名分支名
git remote add origin ssh的地址
git push -u origin 分支名
```

```
git branch -d 分支名  //删除分支
git status //查看状态
git diff //比对修改前后的内容
git branch -v 	//查看分支
git remote -v   //查看远程地址
git reflog  	//查看历史记录

git branch -r -d oring/分支名   //远程分支删除
git branch -a				   //本地查看
git checkout -b 分支名    	     //创建并切换分支

git config --list 				//查看本地配置
git config  --global user.name  '你的目标用户名'   //修改用户名
git config  --global user.email '你的目标邮箱名'  //修改密码

git remote remove origin  //断开远程关联的origin地址

```

```
冲突解决
在进入冲突状态后，修改文件，然后通过git add .
git status查看当前状态
利用commit解决
```

