<p align = "center"><b>图书馆读者服务平台</b></p>
<p align = "center"><b>用户手册</b></p>
<p align = "center">版本1.0</p>

# 1. 引言
## 1.1 编写目的
编写此用户手册是为了充分叙述本系统用户端所能实现的功能以及其运行环境，让用户了解图书馆读者服务平台，了解本系统的使用范围和使用方法。

## 1.2 项目背景
目前，人类的生活节奏加快，人们的阅读时间大大减少。在阅读的时候如何选择自己心仪的书籍就显得尤为重要。本系统通过让用户可以评论和查询书籍，对不同的书籍有一个更好的了解，更好的选择自己要阅读的书籍，选择自己要借的书籍。

## 1.3 参考资料
用户手册介绍：http://wiki.mbalib.com/wiki/%E7%94%A8%E6%88%B7%E6%89%8B%E5%86%8C  
[软件需求规格说明书](./software_requirements_specification.md)

# 2. 系统简介
## 2.1 系统用户
本系统主要面向阅读爱好者。  
喜欢阅读的人群，通过评论书籍分享自己的心得，或者了解不同书籍的相关内容。

## 2.2 运行环境
本系统为在线网站。  
用户可以通过在浏览器输入网站链接来访问该系统。（说明：推荐在电脑端使用新版谷歌浏览器来访问该网站，使用其他浏览器界面的显示可能会出现问题）

# 3. 网站使用
## 3.1 新用户注册
网站首页有**注册**按钮。用户通过点击该按钮进入注册界面。
之后填写**用户名**，**密码**和**邮箱**。用户名需要是字母，数字和下划线的组合（长度为6-16个字符）。密码长度为16个字符。邮箱需要是可以接受邮件，正常使用的邮箱。  
填写号用户名和密码，系统会自动验证用户名和密码是否合法（包括用户名是否已经存在），给出提出合法或者不合法的提示。
填写好用户名，密码和邮箱之后，点击**注册**按钮。等待邮箱验证（用户需要在受到邮件之后进行确认）之后，即可注册成功。  
在填写过程中，用户也可以随时点击**重置**按钮重置用户的所有输入。

## 3.2 用户登录
### 1) 用户登录
已经有了本网站账号的用户可以直接点击**登录**按钮进入登录界面。然后输入**用户名/邮箱**和**密码**。之后点击**登录**按钮进行登录。  
### 2) 重置密码
用户如果忘记密码，也可以在登录界面通过点击**忘记密码**按钮来进入重置密码的界面。  
在重置密码的界面，输入用户账号绑定的邮箱，然后点击**重置密码**按钮，之后系统会重置用户的密码，并且发邮件到用户的邮箱。用户凭借邮件中的密码登录系统。

## 3.3 个人心中
### 1) 查看个人信息
用户登录成功后，可以点击**个人中心**，进入个人中心，查看用户的一些基本信息。包括用户名，性别，邮箱，电话号码，自我介绍等等。
### 2) 修改个人信息
用户可以对其中一些信息进行修改和补充。例如注册时性别和自我介绍没有硬性要求。用户通过选择**修改个人信息**选项，进入修改信息的页面，然后修改其中的一些信息，或者对其中的一些信息进行修改你。
### 3) 查看书单的借记信息
在个人中心，用户选择**我的书籍**选项，可以查看用户的书单，也可以查看到用户的预约记录，借书记录以及归还和未归还的记录。

## 3.4 消息中心
进入**消息中心**之后，用户可以看到有多少条新信息。包括系统信息，评论信息（其他用户对你的评论进行了恢复，或者表示赞同，表示不赞同，举报）等等。

## 3.5 书籍检索
### 1) 搜索框搜索书籍
用户在搜索框，输入想要查找的书籍的名称或者是作者的名称。点击**搜索**按钮来搜索书籍（使用模糊匹配搜索，如何不确定整本书的名称，可以输入书籍名称包含的一些关键词）。之后系统给出搜索结果。
### 2) 查看书籍介绍
用户在系统给出搜索结果之后。通过选择结果中的书籍向查看该书籍的一些相关信息，包括书籍名称，作者，出版社，ISBN编号，书籍评分，书籍状态，书籍简介等等。  
用户在系统的主界面也可以看到系统给出的热门书籍。通过点击不同的书籍来查看不同书籍的介绍，通过此方法看到的书籍的相关信息和上个方法（通过搜索）看到的书籍的相关信息是一样的。

## 3.6 预约
用户查看书籍的相关信息之后，如果想要向图书馆借这本书，但又担心被别人先借去了，可以点击预约，预约该书籍。之后再去图书馆借书。

## 3.7 借书与还书
用户的借书与还书需要到图书馆的借书/还书处，由相关人员呢办理响应的借书/还书手续。  
（该部分属于线下操作，不涉及到用户对该网站的使用，故在此不予以说明）

## 3.8 书籍的评分与评论
### 1) 评分
在查看书籍信息的时候，点击**评分**按钮，弹出评分页面，总共有5个选项可以选，分别是1， 2， 3， 4， 5。数字越大，代表评分越高，对书籍的认可度比较高。选择好分数之后，点击**评分**按钮提交你的评分。如果不想评分也可以关闭评分页面。  
每个用户对一本书只有一次评分的机会，不可以修改评分。
### 2) 评论
在最下面的评论框输入你的评论内容。之后点击**提交**按钮提交你的评论。一个用户可以对同一本书进行多次评论。

## 3.9 评价用户评论
### 1) 查看评论
选择**查看评论**，查看其它用户对该书籍的一些评论。这些评论可能对你了解这本书的内容有帮助。同时，还可以看到其他人对这条评论的态度（同意/不同意）以及回复。
### 2) 表明态度
如果你对某条评论表示赞同，你可以通过点击评论右上方的同意标志来表示赞同。如果不喜欢，也可以点击不同意的标志来表示你不认可该评论。  
如果你感觉这条评论属于恶意评论或者毫无意义等等，你可以点击**举报**，选择举报的理由，然后**提交**你的举报理由。
