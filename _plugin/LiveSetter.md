---
# hide: true
title: 管理直播间小工具
auther: Executor丶
plugin_author: Executor丶
plugin_name: 管理直播间小工具
plugin_desc: 管理你的直播间
plugin_version: 1.0.10
plugin_update_datetime: 2017-05-17 04:12:34 +0800
plugin_update_desc: |-
  更新了检测当前分区的逻辑
plugin_dllink: /resource/LiveSetter/LiveSetter.zip
plugin_dlnote: 只在弹幕姬官网及论坛提供下载,请勿转载
---

若插件有任何问题，亦或对插件有建议，请发邮件至 847529602@qq.com

**※本插件依赖.NET Framework 4.6.2框架,若你的计算机中缺少此框架,可能会导致插件无法正常工作※**

※支持使用**登录中心**插件登录

插件界面
---
<img class="shadow" src="https://www.danmuji.cn/resource/LiveSetter/preview.png" alt="插件界面" />

插件功能
---
- 修改直播间标题、分区、标签
- 开播/关播、获取推流码
- 获取个人信息
- 切换直播间背景(暂不支持上传和删除)
- 切换直播间封面(暂不支持上传和删除)
- 任命/取消房管
- 禁言/解禁用户
- 设置/取消全局禁言

安装方法
---
下载文件后直接放进 `我的文档\弹幕姬\plugins\` 重启弹幕姬即可。

使用说明
---

第一次运行时会创建目录 `我的文档\弹幕姬\plugins\LiveSetterDll\` 并在该目录下释放文件 "Gma.QrCodeNet.Encoding.dll" 用来支持二维码登录。

也会在上述目录下创建目录 `description` 目录用来备份直播间页面的所有代码,以防简介丢失

**用户的cookie保存在 `我的文档\弹幕姬\plugins\cookie` 目录下，请勿将目录下的文件给予他人!**

本插件所有功能均在管理页面中，移步至 **插件** 选项卡并右键本插件，点击 **管理** 即可。



更新日志
---
- 2017-05-17 12:12:34 更新了检测当前分区的逻辑
- 2017-05-10 04:22:46 ※重要※更新了修改分区的逻辑
- 2017-05-04 14:32:46 修复了自动更新的bug(还是C#比较友好)
- 2017-05-04 13:22:58 优化了自动更新的实现,使其能够准确定位dll的位置
- 2017-05-03 18:32:31 修复了封面无效时仍然可以进行更改操作的bug,优化了登录过程中请求的实现
- 2017-04-26 14:10:00 投放至弹幕姬官网,并添加自动更新功能
- 2017-04-22 17:21:44 ※重要※重写了获取简介的方法，以保证能够正确地提交简介信息
- 2017-04-08 17:50:00 添加了打开自己的直播间按钮
- 2017-04-07 17:31:40 修复了字体错位，房管列表加载失败的问题
- 2017-04-05 17:45:46 添加"刷新本页信息"功能。修复了刷新信息时无法显示全局禁言剩余时间的bug
