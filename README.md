# weixinMonitor
微信消息列表信息的监听，当前主要针对版本6.5.10
适用于Android的微信版本客户端，是一个简易版本的微信监听机器人，原理类似于微信抢红包插件，监听微信app的界面渲染回调。
实现的功能包括：
1.监听并记录用户与别人的聊天会话并保存于数据库中，并实现了从上一次会话截止位置开启本次聊天记录的存储
2.循环遍历聊天对话列表，直到微信气泡数量消失。 
3.模拟用户的点击以及来回滚动功能，使得消息都能够实时被记录

需要开启辅助功能选项，从而开启循环便利并监听微信消息的回调。