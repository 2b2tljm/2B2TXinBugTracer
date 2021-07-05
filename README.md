# 2B2T.XIN 漏洞跟踪项目
## 这个项目是在干什么?
这个项目是追踪2B2T.XIN的漏洞/Bug,进行评级并记录的项目
## 这个项目的记录格式是什么?
这个项目使用Markdown进行记录,你可以复制```LBT-example.md```文件并编辑
## 漏洞分级有哪些
### Keter(六级)
最高级别漏洞,具有使服务器进入长期瘫痪状态的能力,或能获取到极高级别权限(如服务器管理权)的漏洞,危及整个服务器的数据安全和存档安全的漏洞
此漏洞破坏性极大,需要***马上处置***
### Euclid III(五级)
此等级漏洞拥有严重破坏服务器稳定的能力(如造成大量密码/账户泄露、造成区块数据大面积损坏缺失或造成大规模的坐标泄露事件)或使服务器在较长的时间内瘫痪的能力的漏洞
此漏洞破坏性较大,需要***马上处置***
### Euclid II(四级)
此等级漏洞可以有一定的权限对服务器的稳定性进行控制(如造成少量密码/账户泄露、造成一定区块数据损坏缺失或造成一定规模的坐标泄露事件),或使服务器在短时间内无法恢复的漏洞。
此等级也包含能造成严重破坏服务器稳定能力,或使服务器在较长的时间内瘫痪但执行攻击较为困难(如需要山水配合等等)的漏洞
此漏洞破坏性较大,需要***马上处置***
### Euclid I(三级)
此等级漏洞可以有少量的权限对服务器的稳定性进行控制(如使得服务器短时间崩溃),或者使服务器流畅程度严重下降的漏洞(指TPS下降到5以下或平均Ping上升到10000ms(10s)以上)(严重卡服漏洞等)
此等级也包含可以有一定的权限对服务器的稳定性进行控制,或使服务器在短时间内无法恢复但执行攻击较为困难(如需要山水配合等等)的漏洞
此漏洞破坏性较大,需要***尽快处置***
### Safe II(二级)
此等级漏洞包含对于服务器平衡性有一定影响(如绕过苍蝇限制、绕过32K限制、反作弊异常),或者使服务器流畅程度一定程度上下降的漏洞(指TPS下降到12以下或平均Ping上升到5000ms(5s)以上)(一般卡服漏洞等)
### Safe I(一级)
此等级漏洞包含对于服务器平衡性有较小影响(如指令失效、点击故障),或者使服务器流畅程度有略微程度上下降的漏洞
### Safe O(零级)
此等级漏洞包含对于服务器平衡性有极小影响(如文字错误、队列问答题目错误)的漏洞
