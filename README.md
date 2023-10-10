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

# 尾声
在Mac上启动会先退出然后等待一段时间后再弹出程序界面，Windows上一切正常

*MacOS 是生活*

*Windows 是工作*

*Linux 是热爱*

***Ubuntu 是偏爱***

# 附录
```
Y  = a * R + b * G + c * B
Cb = (B - Y) / d
Cr = (R - Y) / e
```

|   |BT.601|BT.709|BT.2020|
|:-:|-----:|-----:|------:|
| a | 0.299|0.2126| 0.2627|
| b | 0.587|0.7152| 0.6780|
| c | 0.114|0.0722| 0.0593|
| d | 1.772|1.8556| 1.8814|
| e | 1.402|1.5748| 1.4746|

```
R = Y + e * Cr
G = Y - (a * e / b) * Cr - (c * d / b) * Cb
B = Y + d * Cb
```

* https://www.itu.int/rec/R-REC-BT.601
* https://www.itu.int/rec/R-REC-BT.709
* https://www.itu.int/rec/R-REC-BT.2020

