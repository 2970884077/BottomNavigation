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
    
###行为交互
（1）用户上拉列表时，隐藏Bottom navigation，下拉列表时，显示Bottom navigation

![](http://ww4.sinaimg.cn/mw690/7ef01fcajw1f1zw7j8vbyg209w0hmu0y.gif)

(2)点击Bottom navigation Icon 的时候，不能打开菜单选择或者其他弹窗操作





  
  
  
 



