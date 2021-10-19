# Unity做MMD所需要的技术栈

> 只针对Unity2019 + BuiltIn管线

----------------

## mmd模型转FBX

https://stereoarts.jp/

1. 先入上面那个网站下载MMD4Mecanim插件

2. 然后去借物论坛下载借物模型

https://bowlroll.net/  
https://www.aplaybox.com/search?value=  
...

pmx文件导入后用插件转换成FBX就可以了,记得设置`Rig`为`Humanoid`  

## 模型动作(分两种,mmd-vmd,普通的FBX)

一般的mmd动画文件是vmd格式的,这个同样在借物网站下载以后转换一下就可以了,

但是我个人推荐用下面这种方法:  

https://www.mixamo.com/#/  
在`mixamo`找到想要的动作,直接下载裸模(`必须带模型`)  
然后将FBX导入到 Unity 中以后转成 `Humanoid` 就可以直接用动作了 


