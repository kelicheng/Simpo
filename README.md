## Simpo
一款快速发布文字和图片到社交网站的macOS菜单栏App，目前支持饭否/Twitter/微博多账户登录、一键发送到多个账户、查看最近消息及通知。

![](https://github.com/KeliCheng/Simpo/blob/master/preview.png)

### tips
- 打开App如果出现提示为未认证作者：
	打开System Preference系统设置 --> Security & Privacy 安全和隐私 --> General --> 点击左下角小锁 --> 
	看是否出现 Open Simpo Anyway, 如果没有，尝试关闭之前出现的提示； 如果有，点击Open Anyway，再重启App

- Twitter／微博登录没有反应：打开默认浏览器重试

- 打开设置（添加账户）／退出：右键点击菜单栏图标

- 切换账户：点击左上角头像；按住 Command ⌘ 键选择多个账户

- Twitter／微博授权后有两个程序被打开：将两个程序都关闭后重启Simpo，或尝试使用Chrome等作为默认浏览器

- 饭否登录：请使用ID或注册邮箱登录。例：饭否主页为 fanfou.com/~example, 则ID为“～example”

- 快捷键：⌘`  切换账户，⌘E 插入颜文字，⌘Enter 发送

- 由于微博API限制，现在发送微博和图片会自带一条weibo.com的链接，并且无法插入话题。暂不建议使用。


### Version
v 1.0.0: 支持饭否多账户登录，可以发送图片和文字。可以自定义字体及背景颜色，管理草稿。
v 1.0.1: 支持Twitter登录
v 1.0.2: 支持微博登录
v 1.1.0: 全新UI，更多自定义选项，新增字体、歌词显示等。
v 1.2.0: 支持一键发送到多个账户；支持查看最近消息以及删除。
v 1.2.1: 支持添加位置、自带Emoji&颜文字；支持查看最近20条提到自己的消息。

### TODO
- 长文字生成图片
- fix bug: 上传GIF图问题
~~- 消息通知~~


### Contact
意见建议或bug反馈，请发起issue或联系微博：[@水云青鹤](http://weibo.com/shuiyunqinghe)

----------

## Simpo
A macOS menubar application to post status to social networks. Supporting Fanfou, Twitter, and Weibo accounts. 

## Features
- Support posting statuses to multiple accounts at one time 
- Customized Font, background color, and style etc. 
- Load recent statuses and mentions, easy to delete and repost 

### tips: 
- in case of showing "unidentified developer" alert: close the alert, go to System Preference --> Security & Privacy --> General --> Open Simpo Anyway 

- if login with Twitter/Weibo account is not responding: open the browser and try again 

- right-click on the menubar icon to open preference (customize background color, font, and manage accounts and drafts) or quit 

- click the profile image to switch account; press cmd to select multiple accounts. 

### contact: 
ikcheng322@gmail.com


