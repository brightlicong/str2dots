# 汉字转点坐标

此代码为 [UR5写字控制](https://github.com/brightlicong/UR5-Writing-Control) 的配套程序，用于生成后者需要的`dots-information`。

运行程序后，生成的图片会储存在`img`文件夹中，相应的点信息会在`dots-information`中分文件夹存放。`ttf`中为程序所需要的字体。

可以在程序中自定义要书写的文字，对应文件名以及所使用的字体。

## 效果图

## Bug

因为`opencv`不支持读取含名字含中文的文件，所以`file_name`请使用全英文。

## 相关连接

VScode + opencv + Python 环境配置

https://blog.csdn.net/qq_39384686/article/details/88142541

VScode + opencv + Cpp 环境配置

https://blog.csdn.net/zhaiax672/article/details/88971248