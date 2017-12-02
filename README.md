# 用文字来绘图

![截图](/screenshot/main.png)

核心代码在Utils.java,用文字代替像素块形成图片的算法原理如下： 
* 1.根据原图片的大小和字体的大小创建一张空白图片 
* 2.把原图片按字体的大小分成若干块，取每一块的像素的颜色的平均值 
* 3.将指定文本以得到的平均颜色画在新建的空白图上


>博文解析：http://blog.csdn.net/e_one/article/details/77259903

