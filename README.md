# Google Voice Auto SMS

<font color=#ff0000>(据说这种方法会被封号，请大家谨慎使用！！！)</font>

本项目为Google Voice保号的Python脚本

可用于青龙面板全自动化保号

需要三个环境变量：
- SENDER_EMAIL 你的Gmail邮箱
- SENDER_PASSWORD 你的应用专用密码
- RECEIVER_EMAIL  接收者的邮箱地址

# 使用方法

首先使用需要保号的Google Voice收一条短信，此时打开Gmail可以看到关于这条短信的一封邮件

复制这封邮件的发件邮箱地址备用

此地址大致格式为 你的GV号.发送者号码.英文乱码@txt.voice.google.com



然后打开下面的网址生成一个应用专用密码

https://myaccount.google.com/apppasswords



然后在脚本中替换sender_email为你GV号所属的Gmail地址，sender_password为应用专用密码，receiver_email为@txt.voice.google.com结尾的邮件地址



方法参考：https://linux.do/t/topic/99191
