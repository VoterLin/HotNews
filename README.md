# HotNews
#### 基于网络爬虫与Flask的新闻信息展示网站。
###### · 每日定时对新闻发布平台进行信息采集
###### · 网站分类展示整合后的新闻
###### · 完整的用户模块, 可 账号注册/邮箱验证/更改密码/更改邮箱 可 发表/编辑/删除 文章, 可 点赞/评论/收藏 文章或新闻

### 网站网址：http://www.voterlin.cn

### 如需本地运行，按以下步骤:
	1.安装python3.6，确保同时安装了pip安装模块。<br>
	2.安装MySQL，配置数据库，创建一个名为news的数据库。<br>
	3.解压HotNews.zip项目压缩包。<br>
	4.打开HotNews\vSQL\db.json 填写相应的MySQL配置数据。<br>
	5.在命令行下打开HotNews文件夹，执行pip install requirements.txt命令导入项目依赖的库。<br>
	6.在HotNews下运行once_start.py立即执行爬虫程序，等待程序运行完成。<br>
	7.在HotNews\App\ 下运行Flask.py之后即可通过浏览器访问。<br>
	8.若需要每日定时执行爬虫程序:<br>
		windows 上执行命令:start /b python start.py<br>
		CentOS   上执行命令:nohup python start.py>output.txt 2>&1 &<br>

如果出现什么问题可以通过以下方式联系我：<br>
邮箱：voterlin@foxmail.com<br>
QQ ：1179662449<br>
