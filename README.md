# 底部导航栏（Bottom navigation）规范指南

###前言：
最近 Google 在Material Design设计规范中加入底部导航栏（Bottom navigation）设计,对此，我会在文末给出个人看法！现在我们先来学习Bottom navigation
 在设计、使用、交互、风格、尺寸的一些规范。水平有限，如理解有误，请多多吐槽。
 
###简单介绍
底部导航栏（Bottom navigation）这种设计在很多 Android App 中都是随处可见的，如支付宝、微信、QQ等都使用了，它让视图的切换变得很简单。

###如何使用
（1）底部导航栏需要有3-5个标签（tab）,并且每个tab选择的视图重要性要相似，对于少于3个tab的情况，是不推荐使用Bottom navigation的。

正确方式：

 <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HajN5eDd2UUtGT00/components_bottomnavigation_usage3.png" width="360" height="300" />
 
 错误方式：
 
 <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HYkp0Z1g0dHJXQ3c/components_bottomnavigation_usage4.png" width="360" height="300" />
 
 （2）如果标签很多，比如有超过了5个这种情况呢？Google也是不提倡使用Bottom navigation的，可以用Drawer navigation替换。
 
 正确方式：
 
 
 <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HZHA1UVAyRFpMVDQ/components_bottomnavigation_usage5.png" width="360" height="300" />
 
  错误方式：
 
  <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HbjhLajFZd0JZbmM/components_bottomnavigation_usage6.png" width="360" height="300" />
  
###风格样式
（1）标签Icons和文字的颜色选择是很重要的，一亮一暗才能有对比，用户才很快知道你选择了哪个，如果五颜六色，你是很难分清选择了哪个的。

正确方式：

 <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HSGh1M0QzNVJvVnM/components_bottomnavigation_style5.png" width="360" height="300" />
 
 错误方式：
 
  <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HdF81WTZGYXNFQXc/components_bottomnavigation_style6.png" width="360" height="300" />
 
 
  
（2）标签的文字说明要简短而有意义，避免太长的，也不提倡太长了换行和省略的方式

正确方式：

 <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HUy13a2EtMnVFN1E/components_bottomnavigation_style1.png" width="360" height="300" />
 
错误方式：
 
  <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HTmdoVlhRUlpBTFU/components_bottomnavigation_style2.png" width="360" height="300" />
   <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HQllNTmFqX1czY2s/components_bottomnavigation_style3.png" width="360" height="300" />
    <img src="https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HNWZBUGhvWVpmS2M/components_bottomnavigation_style4.png" width="360" height="300" />
    

####注意：
* 1. 选中的标签要展示高亮图标和文字
* 2. 如果是3个标签的时候，要展示Bottom navigation bar中所有的图标和文字
* 3. 如果是多余三个标签的情况，没选中的tab只需要展示图标就可以，不用文字说明

    
###行为交互
（1）用户上拉列表时，隐藏Bottom navigation，下拉列表时，显示Bottom navigation

![](http://ww4.sinaimg.cn/mw690/7ef01fcajw1f1zw7j8vbyg209w0hmu0y.gif)

(2)点击Bottom navigation Icon 的时候，不能打开菜单选择或者其他弹窗操作，而只是刷新当前视图的内容，如下图：

![](http://ww3.sinaimg.cn/mw690/7ef01fcajw1f1zwkyevefg209w0hm4gx.gif)

(3)不推荐使用手势在视图内容区域切换视图

正确方式：

![](http://ww4.sinaimg.cn/mw690/7ef01fcagw1f1zwwyi12mg209y0hmx5p.gif)

错误方式：

![](http://ww1.sinaimg.cn/mw690/7ef01fcagw1f1zwz18jkkg209y0hmx6p.gif)

###尺寸设计
（1）Bottom navigation对于尺寸的要求还是挺严格的，标签选中和没选中都有细微的差别。

![](https://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B3321sZLoP_HcV9maGFKNVN1STQ/components_bottomnavigation_spec_fixed1.png)






