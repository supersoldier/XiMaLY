# XiMaLY

新特性：
1.多加入了几个界面，完善了几个接口。作为毕业设计，去掉了论坛这个公司的功能。

2.登录界面的数据是在Class-我-Controller-UserAccount.plist文件中 如果不清楚先使用,账号 admin 密码 admin  玩玩。

3.启动图

仿做喜马拉雅, 对AVFoundation框架的一次尝试
# 软件环境：	iOS9.1
# 硬件环境：	Mac OS X 10.11
# 开发工具：	Xcode7.1
项目描述：	模板是“喜马拉雅FM”,因为很喜欢这个软件的风格和内容，当时这款软件参杂着太多的广告以及推广。所以打算通过抓包，并Json解析出数据，进而使用自己搭建的界面完成视听播放功能， UI也算是高仿“喜马拉雅FM”.但部分内容在原来基础上做了相应的修改。 

功能概述： 

0、音频播放：这是最基础的模块，提供用户收听各类声音、专辑及电台主播。 

1、发现听：实时动态的信息展示页，每天的音频热门信息和音频专辑集数的更新；展示给用户声音分类和电台及网络主播相应的推荐页供用户选择交互。 

2、定制听：记录用户关注的声音（专辑）、主播和电台以及收听历史，并推荐近几天热门声音。 

3、下载听：记录用户下载记录并对用户下载过的声音进行分类展示。

4、搜索功能：根据热词提供展示，用户可以搜索主播、电台、声音或专辑。

# 项目所用技术及框架：【纯代码+Xib】项目使用MVVM模式搭建

1、二次封装AFNetworking与MJExtension进行数据请求与解析；

2、使用Masonry实现纯代码布局，使用MJRefresh实现下拉刷新上拉加载；

3、大量使用自定义Cell、自定义Button、自定义View来实现多控件封装方便布局使用；

4、使用AVFundation实现在线音频播放。并自定义播放器外观以及进度条配置；
# 项目收获：

1、对MVVM模式的使用更加熟练,设计模式的了解及掌握为未来开发少走了许多弯路；

2、熟悉JSON数据解析,对数据处理有一定的了解，特别是掌握了MJExtension框架的原理及写法；

3、通知中心及单例模式的使用,减低了代码的耦合性；

4、纯代码跳转Storyboard或者Xib使用更加熟练；封装了好多自定义视图，方便布局。
