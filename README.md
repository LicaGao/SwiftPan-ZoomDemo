# SwiftPan-ZoomDemo
### 11月10日练习
###### 今天写的练习内容相对多一点，重点有两个：
* pan拖拽手势的使用，根据拖拽偏移量计算一些相关数值以实现实时的动画效果，同时也复习了动画和tableView的使用
* 将imageView嵌套在ScrollView中，以此实现图片的放大效果
###### 一些细节：
* 实现父视图半透明而子试图不透明的效果，可以通过设置backgroundColor = UIColor.black.withAlphaComponent(//这里设置透明度)来实现
* 如果要对UIImageView添加手势等，需要先设置imageView.isUserInteractionEnabled = true
