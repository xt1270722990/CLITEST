# CLITEST
我自己整理的Mac版手把手教程：

首先你有一个Github账号，然后去关注5个人，然后找一个人关注你
登陆你的Github，点右侧边栏中的your repositories
 
点选New 去创建公共仓库随便起名字；
选择Public；勾选Add a README file
点Create repository

create了之后 README.MD 就随便给他写东西上去就好了

之后打开Mac上面点终端Terminal

输入：
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
这一步安装nvm

输入：
nvm install 18.18.2
这一步安装node 18.18.2，官方推荐用这个版本

输入：
node -v
检查版本是否正确

输入：
npm install -g @nocturne-xyz/nocturne-setup
开始安装协议CLI

输入：
nocturne-setup auth
这一步是使用Github账户验证CLI（记住账号要满足那三个要求）

输入：
nocturne-setup contribute
开始运行，从这时候开始，请保持你的电脑为开机并且不会睡眠的状态，直到11月6号结束。
