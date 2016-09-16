# demo介绍
    这是我学习慕课网scott的课程[node+mongodb建站攻略](http://www.imooc.com/comment/75)的源码，
    静态页面+静态数据（伪造数据），对windows友好
# 结构
Imooc

  + node_modules
   - XModules
  + bower_components
   - bootstrap
   - jquery
  + views
   - include
    * head.jade
    * header.jade
   - pages
    * index.jade
    * detail.jade
    * admin.jade
    * list.jade
   - layout.jade
  + app.js
        
# 注意
    1、适合windows环境,与Mac有地方不同，具体看源码研究
    2、注意express、jade、moment、mongoose、body-parser、serve-static、bootstrap、jquery模块和各个文件的位置
