1. 注册好github账号后。
2. 打开git bash，输入：ssh-keygen -t rsa -C youremail
3. 直接回车，之后会让你输入github的账号密码，会出现如图所示结果，跟着上面所指示的路径，在你的电脑中找到该文件，id_rsa文件即是你的私有密钥，id_rsa.pub是共开密钥 
4. 打开你的id_rsa.pub文件，复制下里面的内容，然后登录进去你的github； 
5. 在右上角账户那里点击头像边上的下拉，出现如图——点击settings进去，找到左侧的SSH Keys,点击， 
6. 在点击Add SSH Key，在title处填入任意的标识，在Key部分里面添加刚才复制的id_rsa.pub文件里的内容，点击添加即可； 
7. 最后一步了，只需测试一下链接是否正常了，接着输入：ssh -T git@github.com，这时会问是否继续连接，我们输入 yes，这样，我们的git配置就完成了。 

参考：[github-如何设置SSH Key](https://www.cnblogs.com/yehui-mmd/p/5962254.html)

2018-12-2





