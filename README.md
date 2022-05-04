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
git branch -M 分支名
git remote add origin ssh的地址
git push -u origin 分支名
```

