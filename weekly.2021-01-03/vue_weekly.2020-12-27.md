大家好！我是超级机器人 UltraBot，今天给大家推送本周 Vue 开源项目 GitHub 趋势周报，本周更新开源项目 70。

[x2rr / funds](https://github.com/x2rr/funds)

Star: 770, Fork: 90

自选基金助手是一款Chrome扩展，用来快速获取关注基金的实时数据，查看自选基金的实时估值情况

>**写了一个 Chrome 扩展，可以实时查看自选基金的涨跌情况，欢迎交流**
>
># 自选基金助手
>自选基金助手，实时查看您关注的基金，助您快速获取实时数据。
>
>可以用来查看您的自选基金的实时估值情况，可以自由的增减自选基金。您的自选基金数据会跟随账号同步。
>## 介绍
>买了基金后，一直想找一款 pc 端的 chrome 扩展插件，毕竟股票的交易时间都是在工作日进行的，可惜找不到，便打算自己写一个，忍痛花费 5 美刀上架扩展商店。扩展的形式很适合上班族，不用打开网站，仅以小窗口的形式展示，不会引起 BOSS 的注意，方便上班摸鱼。
>
>首先输入基金代码添加基金，将基金添加特别关注后，可以以角标的形式展示在浏览器中，更加简便直观。可以在设置中单独开启显示份额与收益选项，在编辑中输入持有的份额，可以计算出每个基金的实时估值与收益，以及总收益。
>### github 地址：[点击跳转]( https://github.com/x2rr/funds)
>## 如何使用
>**强烈推荐使用 Chrome 商店安装**（这样才能获得自动更新）：[点击跳转至 Chrome 扩展商店]( https://chrome.google.com/webstore/detail/dhdelcemeednchdmijiocipbjlknndff)
>
>若因网络问题，可以下载 CRX 文件手动安装（非常不建议）：[下载地址 1]( https://github.com/x2rr/funds/releases)　　[下载地址 2]( https://gitee.com/rabt/funds/releases)
>
>插件已上架 Microsoft Edge 扩展商店：[点击跳转至 Microsoft Edge 扩展商店]( https://microsoftedge.microsoft.com/addons/detail/kophadiajpobbfoobhclbobddkoindoi)
>
>插件已上架火狐 Firefox 扩展商店：[点击跳转至火狐 Firefox 扩展商店]( https://addons.mozilla.org/zh-CN/firefox/addon/choose-funds/)
>
>![主界面 1]( https://x2rr.github.io/funds/image/1111.png)
>
>![主界面 2]( https://x2rr.github.io/funds/image/2222.png)
>                                        -- rabt



[view-design / ViewUI](https://github.com/view-design/ViewUI)

Star: 2,063, Fork: 599

A high quality UI Toolkit built on Vue.js 2.0

>**【工具】Easy-Monitor —— 基于 Addon 的企业级 Node.js 性能监控开源工具**
>
>欢迎加入官方钉钉群 **35149528** 一起讨论
>
>如果项目对你有帮助，访问 https://github.com/hyj1991/easy-monitor 来 star 支持下作者。
>
>## I. 项目简介
>作为一名 Node.js 开发者，深知对于初涉服务端领域的前端同学来说，在引入 Node.js 的时候很容易心里没底：
>- 我的应用内存一点点上涨，是为什么呢？
>- 我的应用为何响应时间这么慢？
>- 我的代码性能瓶颈在那里呢？
>- ...
>
>[Easy-Monitor](https://github.com/hyj1991/easy-monitor) 是一款Node.js 应用性能监控与线上故障定位解决方案。
>
>旨在 Node.js 的开源生态工具链上，做一些能帮助到想使用和正在使用 Node.js 的开发者更好地感知自己的 Node.js 应用状态，以更好地面对来自性能和稳定性方面的挑战。
>
>**3.0 具备以下新特性：**
>- 针对 Node.js 进程与系统指标的性能监控
>- 错误日志展示与依赖 Npm 模块安全风险提示
>- 自定义智能运维告警与线上进程实时状态导出
>
>对比起 AliNode 等前辈，Easy-Monitor 提供了：
>- 私有化部署能力。
>- 低侵入性，通过 Addon 的方式提供能力，无需定制 Node.js Runtime，能更快的跟进上游。
>- 支持 Linux、macOS、Windows 三大操作系统。
>
>![image](https://user-images.githubusercontent.com/19908330/87736607-2b027c00-c80b-11ea-9ca3-2d834d6879f3.png)
>
>- 文档地址：[https://github.com/hyj1991/easy-monitor](https://github.com/hyj1991/easy-monitor)
>- 源码地址：[https://github.com/X-Profiler](https://github.com/X-Profiler)
>
>## II. 整体架构
>Easy-Monitor 经过了 1.x，2.x 两个大版本的功能迭代，目前的 3.0 版本是作者在 Node.js 监控侧的又一个阶段性总结，对这部分感兴趣的同学可以查看 [前世今生](https://www.yuque.com/hyj1991/easy-monitor/past-and-present)。
>
>目前实现了对 **Window**、**Linux** 和 **MacOS** 三大平台的 Node.js 应用监控支持，整体设计架构如下所示：
>
>![image](https://user-images.githubusercontent.com/19908330/87736676-61d89200-c80b-11ea-96d0-f7b139be06f7.png)
>
>控制台前端基于 [Vue.js](https://vuejs.org/) + [iView UI](https://github.com/view-design/ViewUI) 框架编写，监控服务端部分则是基于 [Egg.js](https://eggjs.org/) 框架编写，UI 部分整体参考了 AliNode 控制台。
>
>更多信息可以访问 [用户手册 - 整体架构](https://www.yuque.com/hyj1991/easy-monitor/architecture) 进行查看。
>
>## III. 部署指南
>参照模块设计图，可以看到项目的部署主要分为两个部分：
>- 部署监控服务端
>- Node.js 应用接入
>
>我们提供了以下 Demo 帮助大家快速体验下 Easy-Monitor 3.0 的能力。
>
>### 控制台
>大家可以访问 [控制台 Demo](http://120.27.24.200:7443/) ，快速体验下新版。（Demo 在代码上做了一些特殊限制防止恶意操作，本地控制台部署参见下文 [完整使用文档](#AT5yW)）
>
>### 应用接入
>我们支持各种 Node.js 应用接入，此处以 Egg.js 为例：
>
>先安装插件：
>
>```bash
>npm i --save egg-xtransit --xprofiler_binary_host_mirror=https://npm.taobao.org/mirrors/xprofiler
>```
>
>启用插件：
>
>```javascript
>// {app_root}/config/plugin.js
>exports.xtransit = {
>  enable: true,
>  package: 'egg-xtransit',
>};
>```
>
>配置接入信息：
>
>```javascript
>// {app_root}/config/config.default.js
>exports.xtransit = {
>  server: 'ws://120.27.24.200:7070',
>  appId: 1,
>  appSecret: 'f7b99d08cc0193106690860047b28970'
>};
>```
>
>对应的 ID 需要访问 [控制台 Demo](http://120.27.24.200:7443/#/app/1/setting) 来注册和获取，如下：
>
>![image](https://user-images.githubusercontent.com/19908330/87736778-a06e4c80-c80b-11ea-99e9-4db98f62e9fa.png)
>
>最后按照正常操作启动 Egg.js 项目即可，正常情况下，你可以在 [控制台 Demo](http://120.27.24.200:7443/) 主页看到本地连接上来的实例：
>
>![image](https://user-images.githubusercontent.com/19908330/87736789-a82df100-c80b-11ea-82a0-8d4b340f3d9a.png)
>
>### 用户手册
>
>目前完整的使用文档部署在语雀上，参见 [Easy-Monitor 3.0 用户手册](https://www.yuque.com/hyj1991/easy-monitor)。
>
>开发者可以根据文档自行部署上述的监控服务端，再将自己的 Node.js 应用接入。
>
>
>## IV. 联系作者
>
>最后的最后，作者是完全使用空余时间维护更新这个项目的，如果项目对你有帮助， 来个 [star](https://github.com/hyj1991/easy-monitor) 支持下作者吧 :)
>
>如果你在使用过程中有任何的疑问或者建议可以提 issue，或者扫码加钉钉群联系作者：
>
><img width="300" src="https://user-images.githubusercontent.com/19908330/87736928-15da1d00-c80c-11ea-94ca-e433eb84bd08.png" />
>
>希望本项目如其名一样，能帮助开发者解决更多开发中遇到的问题，构建起对 Node.js 技术栈的信心，让 Node.js 更加 “简单”。
>                                        -- hyj1991



[YanxinNet / uView](https://github.com/YanxinNet/uView)

Star: 2,192, Fork: 402

uView UI，是uni-app生态最优秀的UI框架，全面的组件和便捷的工具会让您信手拈来，如鱼得水

>uniapp小程序开发者的福音，uView UI，是uni-app生态最优秀的UI框架，全面的组件和便捷的工具会让您信手拈来，如鱼得水开源地址：
>https://github.com/YanxinNet/uView#%E9%A2%84%E8%A7%88
>                                        -- 小米辣开源项目推荐官



[Molunerfinn / PicGo](https://github.com/Molunerfinn/PicGo)

Star: 11,780, Fork: 1,223

🚀 A simple & beautiful tool for pictures uploading built by vue-cli-electron-builder

>**Picgo 图片上传+管理新体验**
>
>## 项目推荐
>- 项目地址：https://github.com/Molunerfinn/PicGo
>
>- 类别：JS
>
>- 项目后续更新计划：https://github.com/Molunerfinn/PicGo/issues/265
>
>- 项目描述：这个应用可以帮助你高效地上传图片到网络图床（本体包括了微博图床、七牛图床、
>腾讯云COS、又拍云、GitHub、SM.MS、阿里云OSS、Imgur，还有一些第三方插件包含了更多的图床，可以在 [Awesome-PicGo](https://github.com/PicGo/Awesome-PicGo) 里寻找），非常方便。只要使用快捷键或拖动就可以上传，而且会自动将图片链接复制到你的剪贴板里。目前支持 MacOS、Windows、Linux 三大系统，使用 Electron-vue 开发。
>
>- 推荐理由：非常方便地上传图片。
>
>- 示例代码：
>
>- 截图：![](https://raw.githubusercontent.com/Molunerfinn/test/master/picgo/picgo-2.0.gif)
>
>
>                                        -- ChungZH



[vueComponent / ant-design-vue-pro](https://github.com/vueComponent/ant-design-vue-pro)

Star: 7,267, Fork: 2,176

👨🏻‍💻👩🏻‍💻 Use Ant Design Vue like a Pro!

>推荐github月度热榜前三的vue开源框架：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/vueComponent/ant-design-vue-pro
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck



[vueComponent / ant-design-vue](https://github.com/vueComponent/ant-design-vue)

Star: 13,277, Fork: 2,122

🌈 An enterprise-class UI components based on Ant Design and Vue. 🐜

>推荐github月度热榜前三的vue开源框架：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/vueComponent/ant-design-vue-pro
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck



[PanJiaChen / vue-element-admin](https://github.com/PanJiaChen/vue-element-admin)

Star: 63,329, Fork: 22,545

🎉 A magical vue admin https://panjiachen.github.io/vue-element-admin

>掘金某位喷子，请尊重别人的劳动成果，花裤衩是我十分敬重的开源作者，他的手摸手给我带来很多帮助，请用代码工具比对如果两个框架代码重合度超过10%，我给你奉上一万元，如果没有请你道歉。
>vue-admin-beautiful最求的永远是最新的package.json，当然可能牺牲了稳定性，追求的更多是漂亮的外观，我承认技术能力可能远不如花大佬，vab的浏览器内存占用明显优化不如花大佬，但我还年轻，我想试试能不能追上他，我要说的话都在下面这张图里，
>
>这是两个框架演示地址：
>http://beautiful.panm.cn
>https://panjiachen.gitee.io/vue-element-admin
>
>这是两个框架开源的地址：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- vab

>掘金某位喷子，请尊重别人的劳动成果，花裤衩是我十分敬重的开源作者，他的手摸手给我带来很多帮助，请用代码工具比对如果两个框架代码重合度超过10%，我给你奉上一万元，如果没有请你道歉。
>vue-admin-beautiful最求的永远是最新的package.json，当然可能牺牲了稳定性，追求的更多是漂亮的外观，我承认技术能力可能远不如花大佬，vab的浏览器内存占用明显优化不如花大佬，但我还年轻，我想试试能不能追上他，我要说的话都在下面这张图里，
>
>这是两个框架演示地址：
>http://beautiful.panm.cn
>https://panjiachen.gitee.io/vue-element-admin
>
>这是两个框架开源的地址：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- vab

>推荐github月度热榜前三的vue开源框架：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/vueComponent/ant-design-vue-pro
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck



[doocs / md](https://github.com/doocs/md)

Star: 1,284, Fork: 167

✍ 一款高度简洁的微信 Markdown 编辑器：支持 Markdown 所有基础语法、色盘取色、一键复制并粘贴到公众号后台、多图上传、一键下载文档、自定义 CSS 样式、一键重置等特性

>**【开源项目推荐】doocs/md：一款高度简洁的在线微信 Markdown 编辑器**
>
>## 介绍
>基于 [wechat-format](https://github.com/lyricat/wechat-format) 进行二次开发的在线微信 Markdown 编辑器。
>
>## 仓库地址
>https://github.com/doocs/md
>
>## 编辑器亮点
>- [x] 支持色盘取色，并一键替换颜色
>- [x] 支持自定义 CSS 样式并实时渲染
>- [x] 支持多图上传并将 URL 插入编辑器光标定位处
>
>## 编辑器地址
>- GitHub Page: https://doocs.github.io/md
>- Gitee Page: https://doocs.gitee.io/md
>
>## 动态图演示
>![](https://github.com/doocs/md/raw/master/assets/images/doocs-md-select-and-change-color-theme.gif)
>
>![](https://github.com/doocs/md/raw/master/assets/images/doocs-md-custom-css.gif)
>
>![](https://github.com/doocs/md/raw/master/assets/images/doocs-md-upload-image.gif)
>                                        -- acbin



[chuzhixin / vue-admin-beautiful](https://github.com/chuzhixin/vue-admin-beautiful)

Star: 7,251, Fork: 1,587

🚀 🚀 🚀 vue3,vue3.0,vue,vue3.x,vue.js,后台管理,admin,vue-admin,vue-element-admin，主线版本基于element-plus、element-ui、ant-design-vue三者并行开发维护，同时支持电脑，手机，平板，切换分支查看不同的vue版本，element-plus版本已发布(vue3,vue3.0,vue,vue3.x,vue.js)

>掘金某位喷子，请尊重别人的劳动成果，花裤衩是我十分敬重的开源作者，他的手摸手给我带来很多帮助，请用代码工具比对如果两个框架代码重合度超过10%，我给你奉上一万元，如果没有请你道歉。
>vue-admin-beautiful最求的永远是最新的package.json，当然可能牺牲了稳定性，追求的更多是漂亮的外观，我承认技术能力可能远不如花大佬，vab的浏览器内存占用明显优化不如花大佬，但我还年轻，我想试试能不能追上他，我要说的话都在下面这张图里，
>
>这是两个框架演示地址：
>http://beautiful.panm.cn
>https://panjiachen.gitee.io/vue-element-admin
>
>这是两个框架开源的地址：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- vab

>掘金某位喷子，请尊重别人的劳动成果，花裤衩是我十分敬重的开源作者，他的手摸手给我带来很多帮助，请用代码工具比对如果两个框架代码重合度超过10%，我给你奉上一万元，如果没有请你道歉。
>vue-admin-beautiful最求的永远是最新的package.json，当然可能牺牲了稳定性，追求的更多是漂亮的外观，我承认技术能力可能远不如花大佬，vab的浏览器内存占用明显优化不如花大佬，但我还年轻，我想试试能不能追上他，我要说的话都在下面这张图里，
>
>这是两个框架演示地址：
>http://beautiful.panm.cn
>https://panjiachen.gitee.io/vue-element-admin
>
>这是两个框架开源的地址：
>https://github.com/PanJiaChen/vue-element-admin
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- vab

>经过三个月辛苦努力，vab框架的标星数量终于超过3K，网站的周访问量也终于过了10万，这世界上嘲笑你的人很多，为了生活，为了梦想，我只能蒙头狂奔，小人物又怎么样，希望10年后，30岁的我会感谢今天没脸没皮，不顾一切的努力。
>演示地址
>https://beautiful.panm.cn
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- vab

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>vue-admin-beautiful是一款基于vue+element-ui的绝佳的中后台前端开发管理框架（基于vue/cli 4 最新版，同时支持电脑，手机，平板）,长期更新维护,感谢您的star,我一直在努力
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck

>推荐一个开源的企业级中后台前端开发框架，定时更新，始终基于最新技术
>演示地址
>https://beautiful.panm.cn/vue-admin-beautiful
>开源地址
>https://github.com/chuzhixin/vue-admin-beautiful
>                                        -- good_luck



[lyswhut / lx-music-desktop](https://github.com/lyswhut/lx-music-desktop)

Star: 9,463, Fork: 1,676

一个基于 electron 的音乐软件



[liupan1890 / xiaobaiyang2](https://github.com/liupan1890/xiaobaiyang2)

Star: 323, Fork: 43

6盘小白羊 第二版 vue3+antd+typescript



[satisfactorymodding / SatisfactoryModManager](https://github.com/satisfactorymodding/SatisfactoryModManager)

Star: 106, Fork: 37

A mod manager for easy installation of mods and modloader



[sdras / intro-to-vue](https://github.com/sdras/intro-to-vue)

Star: 2,349, Fork: 502

Workshop Materials for my Introduction to Vue.js Workshop



[coreui / coreui-free-vue-admin-template](https://github.com/coreui/coreui-free-vue-admin-template)

Star: 2,668, Fork: 743

CoreUI Vue is free Vue admin template based on Bootstrap 4



[surmon-china / surmon.me](https://github.com/surmon-china/surmon.me)

Star: 1,563, Fork: 457

🆒 My personal website and blog, powered by @vuejs (3)



[githyw / column](https://github.com/githyw/column)

Star: 207, Fork: 32

使用Vue3模仿知乎专栏做的专栏



[ThatGuySam / doesitarm](https://github.com/ThatGuySam/doesitarm)

Star: 2,006, Fork: 87

🦾 A list of reported app support for Apple Silicon and the new Apple M1 processor



[lin-xin / vue-manage-system](https://github.com/lin-xin/vue-manage-system)

Star: 11,790, Fork: 4,122

基于vue + element的后台管理系统解决方案



[elrumo / macOS_Big_Sur_icons_replacements](https://github.com/elrumo/macOS_Big_Sur_icons_replacements)

Star: 2,990, Fork: 181

Replacement icons for popular apps in the style of macOS Big Sur



[sdras / ecommerce-netlify](https://github.com/sdras/ecommerce-netlify)

Star: 1,051, Fork: 292

🛍 A JAMstack Ecommerce Site built with Nuxt and Netlify Functions



[zwpro / coupons](https://github.com/zwpro/coupons)

Star: 776, Fork: 171

美团饿了吗红包，先领红包再下单。外卖红包，cps分成，别人领红包下单，你拿佣金。



[Alaanor / beatlist](https://github.com/Alaanor/beatlist)

Star: 184, Fork: 25

Beatlist is an app to manage playlists and beatmaps for the game Beat Saber.



[meteyou / mainsail](https://github.com/meteyou/mainsail)

Star: 219, Fork: 41

A Klipper webinterface made by VoronDesign



[openhab / openhab-webui](https://github.com/openhab/openhab-webui)

Star: 96, Fork: 81

Web UIs of openHAB



[sapic / sapic](https://github.com/sapic/sapic)

Star: 191, Fork: 22

A useful tool to crop your Steam profile background for showcases.



[newbee-ltd / newbee-mall-vue-app](https://github.com/newbee-ltd/newbee-mall-vue-app)

Star: 718, Fork: 216

新蜂商城前后端分离版本-前端Vue项目源码



[chaitin / xray](https://github.com/chaitin/xray)

Star: 4,626, Fork: 952

一款完善的安全评估工具，支持常见 web 安全问题扫描和自定义 poc | 使用之前务必先阅读文档



[directus / directus](https://github.com/directus/directus)

Star: 9,359, Fork: 837

Open-Source Data Platform — Directus wraps your new or existing SQL database with a realtime GraphQL+REST API for developers, and an intuitive admin app for non-technical users. 🐰



[vuejs / docs-next](https://github.com/vuejs/docs-next)

Star: 858, Fork: 366

Vue 3 core documentation



[tokyo-metropolitan-gov / covid19](https://github.com/tokyo-metropolitan-gov/covid19)

Star: 5,989, Fork: 2,050

東京都 新型コロナウイルス感染症対策サイト / Tokyo COVID-19 Task Force website



[weilanwl / ColorUI](https://github.com/weilanwl/ColorUI)

Star: 9,902, Fork: 1,829

鲜亮的高饱和色彩，专注视觉的小程序组件库



[DataV-Team / DataV](https://github.com/DataV-Team/DataV)

Star: 4,059, Fork: 797

Vue数据可视化组件库（类似阿里DataV，大屏数据展示），提供SVG的边框及装饰、图表、水位图、飞线图等组件，简单易用，长期更新(React版已发布)



[wangeditor-team / wangEdior-with-vue](https://github.com/wangeditor-team/wangEdior-with-vue)

Star: 24, Fork: 23

wangEditor 在 vue 中的使用



[biaochenxuying / blog-vue-typescript](https://github.com/biaochenxuying/blog-vue-typescript)

Star: 1,159, Fork: 338

vue + typescript + element-ui 支持 markdown 渲染的博客前台展示



[hoppscotch / hoppscotch](https://github.com/hoppscotch/hoppscotch)

Star: 26,254, Fork: 1,740

👽 A free, fast and beautiful API request builder used by 100k+ developers. https://hoppscotch.io



[iview / iview](https://github.com/iview/iview)

Star: 23,655, Fork: 4,221

A high quality UI Toolkit built on Vue.js 2.0



[element-plus / element-plus](https://github.com/element-plus/element-plus)

Star: 7,141, Fork: 587

🎉 A Vue.js 3.0 UI Library made by Element team



[ElemeFE / element](https://github.com/ElemeFE/element)

Star: 48,654, Fork: 12,043

A Vue.js 2.0 UI Toolkit for Web



[woai3c / visual-drag-demo](https://github.com/woai3c/visual-drag-demo)

Star: 229, Fork: 109

可视化拖拽组件库 DEMO



[chrisvfritz / vue-2.0-simple-routing-example](https://github.com/chrisvfritz/vue-2.0-simple-routing-example)

Star: 1,542, Fork: 752

A simple example of routing with Vue 2.0 without using vue-router.



[dcloudio / hello-uniapp](https://github.com/dcloudio/hello-uniapp)

Star: 1,393, Fork: 957

uni-app框架演示示例



[macrozheng / mall-admin-web](https://github.com/macrozheng/mall-admin-web)

Star: 7,563, Fork: 4,757

mall-admin-web是一个电商后台管理系统的前端项目，基于Vue+Element实现。 主要包括商品管理、订单管理、会员管理、促销管理、运营管理、内容管理、统计报表、财务管理、权限管理、设置等功能。



[lusaxweb / vuesax](https://github.com/lusaxweb/vuesax)

Star: 4,739, Fork: 625

New Framework Components for Vue.js 2



[airyland / vux](https://github.com/airyland/vux)

Star: 17,340, Fork: 3,862

Mobile UI Components based on Vue & WeUI



[abhisheknaiidu / awesome-github-profile-readme](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

Star: 4,716, Fork: 672

😎 A curated list of awesome Github Profile READMEs 📝



[TaleLin / lin-cms-vue](https://github.com/TaleLin/lin-cms-vue)

Star: 1,837, Fork: 404

🔆 Vue+ElementUI构建的CMS开发框架



[infinityu / mina-wear-mask](https://github.com/infinityu/mina-wear-mask)

Star: 427, Fork: 97

头像加口罩小程序 - 基于uniapp使用vue快速实现



*****

以上就是本期推荐的内容，欢迎留言交流。扫码关注如下微信公众号，定期获取开源项目或书籍推荐。

![wechat](https://7465-test-3c9b5e-1258459492.tcb.qcloud.la/common/ultrabot-qrcode.png)

