# **Welcome to My Blogs**

# Reflector
-------------------------------------------------
1. 下载[Reflector](https://www.red-gate.com/dynamic/products/dotnet-development/reflector/download);

2. 破解
    * 运行注册机，点击 Generate 获得序列号；
        ![Install](/Image/Reflector/ReflectorPatch.png)
    * 把序列号填写到 Reflector 软件上；
    * 断开网络，点击 Activate 激活；
    * 提示说无法连接服务器，点击手动激活 Manually Activate；
    * 拷贝 Reflector 左侧的一大堆请求字符串，粘贴到注册机左侧框框，会自动计算注册码；
    * 拷贝注册机右侧的注册信息，粘贴到 Reflector 右侧，激活完成；

3. 反编译存放源代码组件，下载组件[Reflector.FileDisassembler.zip](http://blog.csdn.net/byondocean/article/details/7554548),解压后得到一些文件，其中 Reflector.FileDisassembler.dll是已经编译好的，其它是它源码;

4. 打开安装好Reflector，在view菜单下的Add-Ins，将Reflector.FileDisassembler.dll添加到里面;
        ![Install](/Image/Reflector/ReflectorConfigure.png)

5. open一个dll***,或mcl为后缀的文件,当然要支持.net的;

6. 选择要反编译的dll（会在列表中显示）,选择Tools－>File Disassembler,在右窗口会出现设置存放源码位置的路径,点击产生就可以了!

# [Python](https://www.python.org/)
---------------------------------------------------
## Python的安装
1. 下载[Python](https://www.python.org/downloads/)   
2. 双击安装包，默认安装即可；

## easyegui安装
1. 下载[Python](http://easygui.sourceforge.net/)
        ![Install](/Image/easygui/easyguiDownload.png)

2. 解压安装文件
        ![Install](/Image/easygui/easyguiInstall.png)

## 为Python配置easygui
    将文件夹中的easygui文件夹，拷贝到Python安装目录：\Programs\Python\Python36
        ![Install](/Image/easygui/easyguiConfig.png)

## [VS2017中安装Python开发环境](https://jingyan.baidu.com/article/597a06433b992e312b524384.html)
## [VS2017中添加Python项目要用到的包](https://docs.microsoft.com/en-us/visualstudio/python/vs-tutorial-01-05)


