A web chatroom using tornado.

TODO
====
* UI
  * 界面美化
  * 消息后台发送，失败时作为一类消息提示
  * 提示加入和离开的用户
  * 显示在线人数/成员名单
  * 来消息中在网页标题中显示新消息数目
  * 允许多行消息
* 每个 HTTP 请求最长 120 秒即返回，出错则提示
* 像 [node chat](https://github.com/ry/node_chat) 那样不需要登录
