# test_compiler

1.打开cmd窗口，运行命令ssh-keygen -t rsa 然后一直按回车，直到这条命令执行完毕
2.在这条命令的运行log中可以看到id_rsa.pub这个文件的路径，打开这个文件，将这个文件中的内容全选，复制
![](https://github.com/yuchuzhi/test_compiler/blob/master/sshkey.PNG)
3.打开github，然后点击右上角用户图标，在弹出列表里选择setting 
![](https://github.com/yuchuzhi/test_compiler/blob/master/github6.PNG)
4.在打开的新页面中，左边找到ssh and GPG keys ,然后选择添加new ssh key，然后将之前复制的内容黏贴到KEY下面的空白框里  
![](https://github.com/yuchuzhi/test_compiler/blob/master/github7.PNG)
5.单机add ssh key，完成ssh 的添加 
![](https://github.com/yuchuzhi/test_compiler/blob/master/github8.PNG)
6.进入到我们之前创建的git 仓库，然后选择ssh, 会看到新的guide  
![](https://github.com/yuchuzhi/test_compiler/blob/master/github9.PNG)
7.进入我们本地的代码的文件夹，如果你的文件夹中有.git文件夹，就删除.git文件夹，没有就跳过删除操作，然后运行以下命令：  
git init  
git add .  
git config --global user.email "you@example.com" 引号里面的邮箱地址必须改成你们自己的可访问邮箱地址，比如我，我就改成git config --global user.email "yuchuzhi@163.com"  
git config --global user.name "Your Name"引号中的名字改成你们自己的可识别的名字，名字是什么没有要求，就是有意义的就行，自己名字的拼音也行  
git commit -m "add files"  
git branch -M main  
git remote add origin   这一行命令你们需要运行你们自己网页上提示的那一条，每个人不一样  
git push origin main  
