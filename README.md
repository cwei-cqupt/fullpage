# fullpage

[默认样式使用示例](http://orionwei.github.io/homework/fullpage/docs/demo.html)
[悬浮菜单使用示例](http://orionwei.github.io/homework/fullpage/docs/demo.html?type=fixedM)
[右侧导航使用示例](http://orionwei.github.io/homework/fullpage/docs/demo.html?type=rightL)
[循环 使用示例](http://orionwei.github.io/homework/fullpage/docs/demo.html?type=loop)

1. 获取fullpage

  下载fullpage文件

2. 引入 fullpage 插件（`dist` 目录下的 JS）：

  ```html
  <script src="fullpage.js"></script>
  ```

3. 初始化 fullpage:

  ```js
   var a = fullpage({
        obj:"#a",    //父容器选择器 最好是id选择器;类选择器和tagname选择器默认第一个
        type:"rightL",  //悬浮菜单： fixedM；右侧导航：rightL；循环：loop
        speed:"fast",   //mid,slow,fast 默认mid ， 
        callback:function() {  //滚屏之后的回调函数
            console.log(this);
        }
    })
  ```
