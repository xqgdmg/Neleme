# 总结
* 1.点击商品详情显示的是 DetailActivity，利用主题android:theme="@style/NoTitleTranslucentTheme"，使他没有标题并且是透明背景。看起来像一个Dialog，类似的，应该也是可以用Dialog写成类似Activity，好处是不需要处理Activity的生命周期，轻便。
* 2.DetailActivity类似Dialog的点击消失的效果：点击+动画+finish。
* 3.BottomSheetBehavior是使用，可参考 https://www.jianshu.com/p/1273effa2c55

# Android 仿饿了么点餐页面

![neleme](https://github.com/wudifamo/TestTinker/blob/master/gif/neleme1.gif)

### 8.4更新-----增加详情页交互
上滑进入详情页 下滑退出  加入购物车按钮收缩展开动画



-------------------------------------------------------------------------------
已实现的功能      
* 顶部嵌套滑动逻辑 
* 分类和商品级联定位
* 添加购物车动画
* 购物车弹窗
* 点击商品后的上滑进入详情下滑退出等逻辑
