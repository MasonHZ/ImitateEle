# ImitateEle
仿饿了么收货地址效果，使用百度地图实现。
>项目中用到了一个地图选点的功能，然后设计人员也没有设计具体的界面，小组长大手一挥，你自由发挥，于是就有了这个。我也很无奈啊~

#### 一.实现思路：
##### 1.观察饿了么的收货地址选择，发现它是用的高德地图，在中心位置有一个地图锚点，所以实现起来，大概就是用的RelativeLayout，中心位置放了一个图标,随着地图的滑动，锚点做一些动画效果，同时配合调用地图api。（具体代码就不贴了，比较冗长，可以见工程具体代码）


##### 2.在地图界面如果没有找到