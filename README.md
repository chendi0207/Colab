#  项目略述
* 对Colab某项目的重写，使代码能够部署在Cloudflare。
* 很好的主（备）用节点，ip比较干净（能上GPT）。
* `注意：本项目获取到的节点延迟低不一定代表速度快（节点的延迟随时发生很大的跳动），反过来也一样；如果发生能打开GPT但是上不了Youtube或者Google请换一个节点重试！！`

* 已经修改成使用订阅转换器（三合一），在代码部分修改`WebToken: 'sub'//此处修改登录密码token`，默认( https://你的域名地址/sub )。

#  部署教程
* 测试项目与实际代码是不一样的，测试项目为了方便测试所以使用另一套代码写。
* 将_worker.js里的代码直接复制到Cloudflare进行部署(或者fork之后pages部署`自行尝试`)，默认Token为sub。
* Pages部署诺要修改Token，增加变量名为`TOKEN`并自行修改，重新部署即可。
* 代码部署到网页之后显示base64编码内容表示搭建成功，网页地址均为订阅链接（不需要复制网页内的base64编码导入软件）。
* 代码已使用订阅转换器，可允许在Nekobox、V2ray、Clash、Singbox等软件进行订阅，其他软件可自行测试。
* `注意：本项目一定要绑自定义域名，否则会获取不到节点信息！！`

##  更多问题请联系：
* [Telegram](https://t.me/Enkelte_bot)

## 赞助支持

[![Yxvm 赞助横幅](https://support.nodeget.com/page/promotion?id=223)](https://yxvm.com/)

本项目由 [Yxvm](https://yxvm.com/) 提供服务器资源赞助，特别感谢他们对开源项目的支持！

[![NodeSupport 开源项目](https://img.shields.io/badge/NodeSupport-Open--Source-%2300a67c?style=flat)](https://github.com/NodeSeekDev/NodeSupport)
