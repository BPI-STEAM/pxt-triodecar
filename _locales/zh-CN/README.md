## Triode-Car

[BPI-TriodeCar是一个为Steam教育而设计的产品](https://www.aliexpress.com/item/1005002522563487.html?spm=2114.12010612.8148356.23.4c7c599eTzy5vr)

## 注意

这个是一个Beta版本

最新的信息请参考这里 http://wiki.banana-pi.org/%E9%A6%99%E8%95%89%E6%B4%BE_Triode-Car

下面是一些我们的教学视频  

Triode Car #1 - A Beginning to Something Big https://www.youtube.com/watch?v=qcR-Haovyr4

Triode Car #2 - Installing Colorful Resistors! https://www.youtube.com/watch?v=z6adIa8id5Y

## 使用方法

### ``控制小车方向``

使用 ``CarDirection`` 积木控制小车

```blocks 
basic.forever(() => {
    triodecar.CarDirection(triodecar.direction.foward)
})
```

### ``巡线传感器的使用``

读取``readPatrol`` 积木状态（高低电平）

```blocks 
basic.forever(() => {
    serial.writeLine("" + (triodecar.readPatrol(triodecar.Patrol.PatrolLeft)))
})
```
## 插件的使用

这个仓库可以作为一个**扩展插件**被加到MakeCode中。

* 打开MakeCode [https://makecode.microbit.org/](https://makecode.microbit.org/)
* 点击 **新建项目**
* 点击右上角齿轮中的 **扩展**菜单
* 搜索 **https://github.com/BPI-STEAM/pxt-triodecar** 然后导入

## 编辑这个项目 ![Build status badge](https://github.com/BPI-STEAM/pxt-triodecar/workflows/MakeCode/badge.svg)

在MakeCode中编辑这个仓库.

* 打开 [https://makecode.microbit.org/](https://makecode.microbit.org/)
* 点击 **导入** 然后点击 **导入网址**
* 粘贴 **https://github.com/BPI-STEAM/pxt-triodecar** 然后点击导入

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
