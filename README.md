## Author: mia yu [personal blog: http://www.jianshu.com/u/b344d2977570]
## Getting Started

实现原理介绍可以看我博客里的文章

打开网页的时候，注意图片跨域问题
若出现如下错误：
Access to Image at 'timg.jpeg' from origin 'null' has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'null' is therefore not allowed access.
虽然代码中有声明img.crossOrigin属性，但貌似不起作用

解决方案：
1. 起个http-server
2. 用safari浏览器是可以直接访问的
