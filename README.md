# yuv2rgb
这是一款将YUV格式的图片转换成常见的RGB格式的图片，预置的RGB类型（bmp，jpg，jpeg，png）

支持图片位深：8，10，12，14，16

yuv格式：基本包含常见的420，422格式

说明文档已经内置在app中，并附带rgb转yuv功能，默认yuv420p，8bits位深

# 主界面
![image](./界面.png)

# 说明文档界面
![image](./说明文档.png)

# RGB转YUV界面
![image](./rgb转yuv.png)

# 后续碎碎念
程序有些问题，app在启动时候会先退出然后等待一段时间再弹出。之前一直用windows，没有这种问题。对于mac不太了解，没有进行优化处理。

在打包app的时候，我不得不感慨一句，windows有些时候还是挺好的，windows用的时间太久了，所以基本上知道怎么搞，mac还不太熟悉，出了些意外，不过都解决了。

不知道arm架构的macos下的虚拟机里面的windows可不可以打包出在x86平台下的exe使用，暂时没有精力，如有windows exe需求，可以找我

MacOS操作系统用起来确实很舒服，十多年的windows用户转换过来，也仅仅只是几天就适应了。习惯命令行的我逐渐发现，很多linux命令在mac上并不存在，
最特别的是 /home/ 目录，原来在MacOS下是作为一种格式，为了和Linux对齐，不允许创建文件夹之类的操作。

用了MacOS才知道Windows的文件浏览器很好用。

体验过三种操作系统后，对于争论谁好用的问题，有了自己的答案。没有标准答案，自己喜欢就好。

``
MacOS是生活，Windows是工作，Linux是热爱，Ubuntu是偏爱。
``
