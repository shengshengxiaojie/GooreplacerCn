# GooreplacerCn 中文版

[![Build](https://oauth.applinzi.com/State/passed/PASSED/44CC11.svg)](../../)
[![Size](https://oauth.applinzi.com/Label/size/491KB/b36d41.svg)](gooreplacercn.crx.zip)
[![tag](https://oauth.applinzi.com/Label/tag/v3.10.0/84bf96.svg)](../../releases)
[![license](https://oauth.applinzi.com/Label/license/MIT/FE7D37.svg)](LICENSE)
[![languages](https://oauth.applinzi.com/Label/languages/JavaScript/c8b218.svg)](../../search?l=JavaScript)

<div align=center><img src="image/04.jpg"/></div>

##### 说明一下，支持原创

本扩展插件并非原创而是通过重新修改和中文翻译得来，源件是 `英文界面` 操作,对于英文不好的国人来说十分不方便 (其实就是我的一个朋友想用，又看不懂英文每次都问我为了摆脱纠缠才修改的) 如果你觉得自己英文不错可以去使用 [原版](https://github.com/gooreplacer/gooreplacer) ，由于时间仓促大多数语句都是翻译软件来完成的，所以部分语句翻译的比较别扭不过相信大家都能理解。

## 介绍

> 重定向，阻止请求；修改，屏蔽请求标头/响应标头 headers

GooreplacerCn 最初为解决国内无法访问 Google 资源（Ajax、API等）导致页面加载速度巨慢而生，新版在此基础上，增加了更多实用功能，可以方便用户屏蔽某些请求，修改 HTTP 请求/响应 的 headers。

## 特性

- 支持在线规则，主要用于重定向 Google 资源，用户可更改
- 本地规则
- 导入导出规则，方便用户备份、同步（规则可在 Chrome/Firefox 种通用）
- 支持测试

## 安装

1 直接下载本仓库的 [crx压缩包](https://github.com/yakeing/GooreplacerCn/raw/master/gooreplacercn.crx.zip)

2 在电脑上任意磁盘新建文件夹，使用英文不区分大小写如： D:/gooreplacercn

3 打开Google浏览器，这里用 Google Chrome 做例子，进入扩展程序中心

> chrome://extensions

![0](image/01.jpg)

4. 启用开发者模式

![0](image/02.jpg)

5 加载正在开发的程序包，选择刚才的文件夹就行了

![0](image/03.jpg)

6 这时候浏览器右上角出现图标点击进入

![0](image/04.jpg)

对于只想重定向 Google 资源的同学，可以在 `联机规则列表` 处填上

[gooreplacer.gson](gooreplacer.gson)

然后点击更新就好了。如果想自定义规则，可参考 [guides.md](guides.md)

## License

[MIT License](LICENSE)
