## GIF

### 引言

![new_year](/Users/zysu/Documents/我的技术文章/GIF图/images/new_year.gif)

### 原理

在**iOS**系统中，通过`[[UIImage alloc] initWithData:data]，[UIImage imageWithData:data]`等系统api直接加载gif图，在图片显示时并不会动。所以动图的加载是需要开发者自己处理的。

系统中提供了一个简单的创建动图的方法：[UIImage animatedImageWithImages:images duration:duration]，这种方式通过提供一个图片数组和动画时间，可以做简单的动图播放。

### 轮子

![lunzi](/Users/zysu/Documents/我的技术文章/GIF图/images/lunzi.jpg)

![my_lunzi](/Users/zysu/Documents/我的技术文章/GIF图/images/my_lunzi.gif)

### 总结

