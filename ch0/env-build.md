##  1. Windows版Python安装与配置    


因为Python是跨平台的，它可以运行在Windows、Mac和各种Linux/Unix系统上。在Windows上写Python程序，放到Linux上也是能够运行的。

要开始学习Python编程，首先就得把Python安装到你的电脑里。安装后，你会得到Python解释器（就是负责运行Python程序的），一个命令行交互环境，还有一个简单的集成开发环境。

### 安装Python 3.8
目前，Python有两个版本，一个是2.x版，一个是3.x版，这两个版本是不兼容的。由于3.x版越来越普及，我们的教程将以最新的Python 3.8版本为基础。请确保你的电脑上安装的Python版本是最新的3.8.x，这样，你才能无痛学习这个教程。


###  在Windows上安装Python
首先，根据你的Windows版本（64位还是32位）从Python的官方网站下载Python 3.8对应的64位安装程序或32位安装程序，然后，运行下载的exe安装包：   

![](https://ipic101-1253790954.cos.ap-beijing.myqcloud.com/2022-10-16-l.png)

特别要注意勾上**Add Python 3.8 to PATH**，然后点“Install Now”即可完成安装。  

###  运行Python
安装成功后，打开命令提示符窗口，敲入python后，会出现两种情况：

情况一：    

![](https://ipic101-1253790954.cos.ap-beijing.myqcloud.com/2022-10-16-Snip20221016_23.png)


看到上面的画面，就说明Python安装成功！

你看到提示符>>>就表示我们已经在Python交互式环境中了，可以输入任何Python代码，回车后会立刻得到执行结果。现在，输入exit()并回车，就可以退出Python交互式环境（直接关掉命令行窗口也可以）。

情况二：得到一个错误：  

![](https://ipic101-1253790954.cos.ap-beijing.myqcloud.com/2022-10-16-111040.jpg)  

这是因为Windows会根据一个Path的环境变量设定的路径去查找python.exe，如果没找到，就会报错。如果在安装时漏掉了勾选**Add Python 3.8 to PATH**，那就要手动把python.exe所在的路径添加到Path中。

如果你不知道怎么修改环境变量，建议把Python安装程序重新运行一遍，务必记得勾上**Add Python 3.8 to PATH**。  


##  2. PyCharm下载与安装  


###  2.1  PyCharm 下载

####  2.1.1  PyCharm 简介

PyCharm 是 Python 最著名的  **集成开发环境(IDE)**  之一，所谓集成开发环境就是将你在开发过程中所需要的工具或功能集成到了一起，比如：代码编写、分析、编译、调试等功能，从而最大化地提高开发者的工作效率。

####  2.1.2 PyCharm 版本

PyCharm 官网提供两个版本：Community 和 Professional，支持 Nindows、Mac、Linux三种操作系统。

Community版本是开源项目，是免费的。Professional 版本功能更强大，是收费的，提供一定时间的免费试用，试用期结束后需要付费。对于初学者而言，Community 版本一般即可满足开发需求，本课程中也将以 Windows 下的 Community版本为例进行讲解。

###  2.1.3 PyCharm 官网下载

PyCharm 官网：https://www.jetbrains.com/pycharm/，下载步骤如下：   

1. 进入下载页面

https://www.jetbrains.com/pycharm/download/#section=windows   

点击 Community 下的“Download“即可，如下图所示    

![](https://ipic101-1253790954.cos.ap-beijing.myqcloud.com/2022-10-18-Snip20221018_6.png)  


2. 安装PyCharm  

PyCharm 安装与设置涉及到不少操作细节，可以观看视频  



3. PyCharm 安装中文插件

PyCharm 提供了免费的中文插件，习惯使用中文界面的小伙伴可以安装中文插件，安装方法如下：

在 PyCharm 的主界面依次点击：File-> settings- plugins-> Marketplace，在打开的 Marketplace 界面中，搜索 chinese，然后点击 InstallB 即可安装插件，如下图所示    

![](https://ipic101-1253790954.cos.ap-beijing.myqcloud.com/2022-10-18-Snip20221018_7.png)













##  Ref  
1. [廖雪峰](https://www.liaoxuefeng.com/wiki/1016959663602400/1016959856222624)
