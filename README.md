# Fantasy Pixel
>  自制取模软件，无限可能



## 前言

我在使用 STM32 绘制 OLED 显示屏的时候想要一帧一帧的绘制图片以达到类似于动图或视频的功能，但是我手中的取模软件只能一张一张地转化图片，操作起来十分的蛋疼。我在网上找到了为数不多的支持批量取模的软件，但是各种参数的支持又不是很到位，于是，我决定自己开发一款取模软件，掌控一切，取名 **Fantasy Pixel**



## 需求

- 取模软件的基本功能都要实现，并且完全可以自定义参数
- 批量图像的取模
- 鉴于目前我手上两款软件的操作逻辑和界面都不尽人意，自己开发的软件 UI 界面和操作逻辑要人性化
- （尝试）实现插件系统，可以方便的扩展软件功能
- （待定）支持更加一键化的操作，比如直接对视频取模（可能要其他第三方库）



## 思路

取模的核心功能实际上非常简单，将一张图片二值化以后，以字节为单位转化成十六进制并输出，然后根据参数排列即可



## 后记

`开发主代码：Python 3.12.7`

`第三方库：pygame 2.6.0`

`开发工具：vscode 1.95.2`

> 文档编写：Fantastair
>
> 日期：2024.11.9
