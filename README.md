# MultiItemRecycleView

前情提要：去面试一家外企，需求是要重复使用一个布局很多次，

单单是布局的话用include就可以了，但是逻辑也要复用，

而且提出了使用listview复用条目优化性能，想做成一个自定义控件。

我尝试了下，感觉直接用recycleview应该也是可以的.




实现思路

    添加依赖
    
    com.android.support:recyclerview-v7:24.2.0
    
    根据需求创建三个不同类型的item对应的布局文件
    
    为每个类型的item创建数据bean类
    
    创建通用的item数据bean类
    
    为每个类型的item创建viewholder
    
    创建Adapter类
    
    在Activity使用recycleview



<img src="https://raw.githubusercontent.com/whtchl/MultiItemRecycleView/master/art/1.png"/>
