<!--text-*文本编辑-->

在此就不详说了

```wxss
.ji{

/* text-align: center;etc; */

}
```

float浮动布局和标准法(//为注释)

```wxss
.ni{
float:left;//紧贴盒子左边；right同上理解
//且float浮动布局和标准法布局可以进行重叠使用
}
```

```wxss
<view style="float:none">1</view>
<view style="float:left">2</view>
<!-- <view style=""></view> -->
<view style="float:none;clear: left; ">3</view>
<view class="" style="float:none">4</view>
```

上边代码浮动型问题，于11月4日讨论解决

```wmtl
<view style="float:none" ><image src="/images/tabs/contact-active.png"></image></view>
<view style="float:left"><image src="/images/tabs/contact.png"></image></view>
<!-- <view style=""></view> -->(此处解除可以解除重叠)
<view style="float:none;"><image src="/images/tabs/home-active.png"></image></view>
<view  style="float:none"><image src="/images/tabs/home.png"></image></view>
```

上述为尝试，可以进行图片重叠^_^

```wxss
view{
  width:100px;
  height: 500rpx;
  background-color: #ccc;
}
.text1{
  float:left;
  
  background-color: pink;
}
.ji{
  background-color: purple;
  height: 200rpx;
}

.kun{
  background-color: skyblue;
}

```

上边是wxss的代码



下边是代码

```xtml
<view>
<navigator class="ji" url="/pages/logs/logs"><text  class="ji">新浪微博</text></navigator>
<text class="ji">手机新浪网</text>
<tetx class="ji">移动客户端</tetx>
<text class="ji">微博</text>
<text class="ji">三个字</text>
</view>
```

```json
  "pages":[
    "pages/index/index",
    "pages/logs/logs"
  ],
```

可以跳转页面

也可以在tabBar中跳转页面

但是需要加 open-type="navigate"

不加将会不能跳转 

## 其他基本学科

高等数学（in other Word，就是上课内容而言）

1.微分中值定理

2.洛必达法则

3.泰勒公式

线性代数（这周星期六还要考试=_=）

1.线性方程组与矩阵的初等变换

2.欧式空间and矩阵的特征值与特征向量

英语没有什么好讲的

就是单纯的背单词

程序设计方面

现在的C语言知识完全超过老师进度

再次不赘述

end...................................................

