资源汇总
========

	汇总有价值的信息，持续更新...
  
## 业界大神

详见：[resources/masters.md](resources/masters.md)

## 站点风格

- http://ylbook.com/cms/web/chuantongsecai/chuantongsecai.htm  
- http://nipponcolors.com/  

## 健康

	健康相当重要，码农这个职业对健康的损害很大，所以我们尤其需要重视。

**112岁老中医的临终馈赠**  
http://mp.weixin.qq.com/s?__biz=MjM5MzEyMjAyMA==&mid=200286062&idx=1&sn=cddbd9a54fe069667ee11b9131ecd24f#rd  
虽说中医是否科学这个话题一直都有争议，但这里给出的很多建议却是对的。

## 专业站点

**http://www.quilt.org/** A little thing to help make your data more computable  
**中国高等植物物种检索词典地方版发布** http://www.planta.cn/forum/viewtopic.php?t=28888  

## 服务

	组织运作、创业中可能用到的东西

**salesforce** : https://www.salesforce.com/ crm  系统  
**slack**  https://slack.com/  
**问卷网** : http://www.wenjuan.com/  
**麦客** : http://www.mikecrm.com/  
**tower** : https://tower.im/  在线协作  fengcheco Basecamp 
**聚合数据** : http://www.juhe.cn/  短信接口比较有用  
**Stash** https://www.atlassian.com/software/stash  Enterprise Git Repository Management  
**Confluence - 内部协作** https://www.atlassian.com/software/confluence  
**云片网** http://www.yunpian.com/  短信平台  
**blog engine** Dropplets github-pages jerrly Hexo poeat ghost  
**icon** GitHub Octicons   http://www.graphicsprings.com/  
**Docker**  
**一分钱不花，开发native应用**: http://www.csdn.net/article/2014-02-11/2818360-mobile-dev-tools  
**vasee** : http://www.vasee.com/ 门票销售和报名收费工具
**风车网** : https://fengcheco.com/ 团队协作工具，简单易用的界面，跨平台移动客户端支持，帮助你更好的管理项目和团队。  
****  http://www.paxata.com/  
****  https://trello.com/  
http://sendcloud.sohu.com/feature.html

## Why I Left  系列

[Why I Left the .NET Framework](http://blog.jonathanoliver.com/why-i-left-dot-net/)  
[Farewell Node.js](https://medium.com/code-adventures/farewell-node-js-4ba9e7f3e52b)  
[Farewell CoffeeScript](https://github.com/staltz/rxmarbles/commit/57e37f176e0e005abd2c4fa0253bbd8f57fe1bd9)


## 规范

- 语义化版本号 Semantic Versioning : http://semver.org/

## 工具使用

### ssh 方式使用 github 

好处在于不用输 github 密码，操作过程 ：<https://help.github.com/articles/generating-ssh-keys>  
处理完成后， clone 时 采用 ssh clone url 即可，类似： git@github.com:zenany/weekly.git  
但如果设置了 ssh passphrase ，在用 git 操作时会提示： Enter passphrase for key  
要避免这个，需要执行如下指令：

	eval `ssh-agent -s`
	ssh-add ssh-add ~/.ssh/id_rsa

参考资料：[Working with SSH key passphrases](https://help.github.com/articles/working-with-ssh-key-passphrases) 、 [Could not open a connection to your authentication agent](http://stackoverflow.com/questions/17846529/could-not-open-a-connection-to-your-authentication-agent)

### chrome cancay 版本不显示文字问题

chrome://flags/ 启用DirectWrite 关闭即可，http://tieba.baidu.com/p/3115276351 贴吧真 NB

#### Autojump 

自动补完不算什么，一键直达目录才是终极神器！

http://xmodulo.com/2014/06/speed-up-directory-navigation-linux-terminal.html  
http://blog.jobbole.com/73611/  

#### Ubuntu 镜像

http://mirrors.163.com/  

#### Git使用

- [专为设计师而写的GitHub快速入门教程](http://www.ui.cn/project.php?id=20957)  
- [CoolGithubProjects](http://www.coolgithubprojects.com/)  

http 方式每次需要输入密码：  
git config --global credential.helper wincred  
https://help.github.com/articles/caching-your-github-password-in-git/  

## Deeplearning & Bigdata

[Deep learning from the bottom up](http://metacademy.org/roadmaps/rgrosse/deep_learning)  
[Toward Scalable Systems for Big Data Analytics: A Technology Tutorial](http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6842585)  
[推荐系统开源软件列表](http://www.resyschina.com/2014/02/open-source-recsys.html)  
[MIT - Deep Learning](http://www.iro.umontreal.ca/~bengioy/dlbook/)  
