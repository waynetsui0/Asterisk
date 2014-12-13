	这一个版本用来测试在ubuntu下github的安装和使用
1、安装比较简单，在ubuntu 软件中心直接搜索 'git hub'然后安装就行了，不用自己通过apt-get 来安装配置。
2、注册一个github帐号
3、生成一个SSH密钥：在git hub 官方网站上有详细的介绍https://help.github.com/articles/generating-ssh-keys/

github 操作的一般步骤
1、本地建立一个git版本
	$ git init
2、然后在版本库中添加示例文件，如README.md文件，内容同前。
	$ git add README.md
	$ git commit -m "README for this project."
为版本库添加名为origin的远程版本库。
	$ git remote add origin git@github.com:gotgithub/helloworld.git
执行推送命令，完成GitHub版本库的初始化。注意命令行中的-u参数，在推送成功后自动建立本地分支与远程版本库分支的追踪。
	$ git push -u origin master
以扩展名.md，.mkd，.mkdn，.mdown，.markdown等为结尾的文件，均以Markdown标记语言语法进行解析并显示。
