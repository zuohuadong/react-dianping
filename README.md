
## 测试题目 

1. 创建一个新的路由 `ibenchu`
2. 使用该接口填充数据，数据需要正常展示出来，对样式没有要求 [微信精选接口](https://mobapi.ibenchu.pw/wx/article/category/query?key=1eae6b9688738&area=CN)
3. 在该项目的首页加上跳转到这个页面的方式（不得使用A标签跳转）


## 注意事项

1. 该测试需独立完成。
2. 面试有可能现场写React代码，请勿抱有侥幸心态。

**完成后请将源码以 `zip/tar.gz/tar.xz` 形式发送到heshudong@ibenchu.com 【注意附带简历】**

我们将在三个工作日内给出答复

===============测试题目===================
## 说明

根据教程[React高级实战 打造大众点评 WebApp](http://coding.imooc.com/class/99.html)，学习react。
并根据自己的理解优化代码。
具体改造如下：

1. 升级为最新的webpack3, react16, react-redux, react-router4，koa2.3等
1. 支持stylus预处理器
2. 提取封装了列表加载更多等组件
3. 其他目录结构调整和es6写法优化
4. 异步按需加载组件

学习过程中总结了几篇react相关[文章](http://www.jianshu.com/p/9cd7a0dff11f)，
不足之处还望批评指正

## 安装

 1. yarn 安装依赖
 2. yarn mock 启动模拟后台服务器，提供api
 3. yarn start 启动前台程序
 
 ![image](https://github.com/mafeifan/react-dianping/blob/master/screenshot/demo.gif?raw=true)
 
## TODO

* 补充组件树图，有自己解析并生成的工具吗
* 封装loading-spinner等组件
* 改造使用flex布局或者尝试grid布局

