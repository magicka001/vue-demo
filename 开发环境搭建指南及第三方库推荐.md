
# 开发环境搭建指南及第三方库推荐
##一般都使用 CocoaPods 来管理第三方代码
CocoaPods是一个负责管理iOS项目中第三方开源代码的工具。
教程：
http://www.jianshu.com/p/f5536485e3a0

##项目目录结构 例子参考

1. 主目录按照业务分类，内目录按照模块分类
![GitHub set up](http://upload-images.jianshu.io/upload_images/295346-94f1461a7ee68d10.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


2. 主目录按照模块分类，内目录按照业务分类
![GitHub set up](http://upload-images.jianshu.io/upload_images/295346-810d6b1cfcb46994.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


可以尝试按照自己的逻辑去归类，或可以多观察下身边大牛搭建的项目，会吸取到其中的奥秘。

##第三方框架推荐（针对swift）
SVProgressHUD  是一个弹出提示层，用来提示 网络加载 或 提示对错。
Alamofire  		 网络请求
SwiftyJSON 		JSON解析
SDWebImage 		图片异步加载 
SnapKit    		自动布局 设置约束


