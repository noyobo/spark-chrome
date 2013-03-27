spark-chrome
============

一款用在Chrome 浏览器上的 虾米音乐 插件

项目地址:
--------
<https://github.com/noyobo/spark-chrome>

**WEB端 地址**
><http://noyobo.sinaapp.com/xiami-ex/>

**crx 安装文件**
><http://192.168.5.117:9527/spark-chrome.crx>

**安装方法**
>chrome 浏览器下 进入[工具-扩展程序]``chrome://extensions/`` 把下载好的 [crx]文件 拖入 后重启浏览器.

插件介绍:
------
**目前已实现的功能:**
*	播放器基本功能
*	歌曲信息 显示`封面\歌名\艺人\收藏状态`
*	收藏歌曲 操作
*	不再播放 操作
*	插件 icon 状态切换
*	插件 icon 播放/暂停 鼠标悬停提示
*	localStorage 本地数据记录 
*	Notifycation 歌曲提示 (悬停 5s)
*	重置歌单 机制

**目前未实现的功能:**
*	无登录模块

  >可先打开 **[虾米网]** 登录后,使用本插件 点击 重置歌单,则播放的歌曲将是根据当前已登录用户收藏曲库获取的歌曲列表.
  
  >未登录用户操作异常提示

*	无推荐理由

更新历史:
---------

**版本 1.3.3 2013年3月26日 14:16:04**
*	增加 WEB页面 UI 展现

**版本 1.3.2 2013年3月12日 13:36:03**
*	增加右键菜单 虾米随身切 
*	删除 快捷键 设置

**版本 1.3.1**
*	修复 Notification 面板点击 播放/暂停 状态不切换
*	增加 Notification 面板鼠标 悬停/滑离 显示控制
*	增加 Notification 呼出快捷键  Shift + ctrl|alt + x  `面板可操作` (快捷键仅在chrome浏览器激活状态下可用)

**版本 1.3.0**
*	偏好比例 设置
*	音量调节 设置
*	自定义 Notification 提醒样式

改进建议:
---------
如果你有更好的改进建议,欢迎下面的地址提交给我 :)
<https://github.com/noyobo/spark-chrome/issues/1>

[crx]: http://192.168.5.117:9527/spark-chrome.crx
[虾米网]: http://www.xiami.com/ "虾米音乐网"
