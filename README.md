# newIDEA2
Java web从入门到精通
·遇到的问题：不理解什么是servlet
·项目能跑通代码点不理解
·安装问题，配置成功tomcat之后，用eclipse打开网页会404（待解决）——解决方案：安装了myeclipse；猜想可能没运行到指定的网站
·安装问题，IDEA版本问题，是免费版还是完整版，免费版不能进行web开发（已解决）
·架构问题，选择JavaEE框架还是Spring MVC框架，经多方调研得知如今流行springmvc和springboot
·了解JavaEE的主要技术
·数据库连接问题
·wang&zhong :打开项目发现https://github.com/ni-ze/ssm-BookAppointment有java版本什么的错误，他说好像跟什么xml文件有关
·xie:重新安装了exe安装版本的汤姆猫，所以建议小白还是安装这个版本的。
·运行时8080端口被占用：两条指令即可解决，成功运行第一个web项目。
  1、C:\Windows\system32>netstat -ano|findstr 8080
  2、TCP    0.0.0.0:8080           0.0.0.0:0              LISTENING       5048

  TCP    10.236.168.120:50297   117.144.244.65:8080    ESTABLISHED     4744

  TCP    10.236.168.120:50674   183.192.192.163:8080   ESTABLISHED     9336

  TCP    [::]:8080              [::]:0                 LISTENING       5048
  C:\Windows\system32>taskkill /pid 5048 /f
  

成功: 已终止 PID 为 5048 的进程。
·wang:引导编写了函数，引导前端组写界面

各组员采用的开发版本：
  Wang:
  ·eclipse jee oxygen JavaEE
  ·tomcat7
  
  Xie:
  ·tomcat9
  ·IDEA 2018.3.5完整版
  配置过程详见：http://blog.sina.com.cn/s/blog_138941a1a0102yrhv.html
  
  Zhong:
  ·Luna 4.4.2 JavaEE
  ·tomcat7
 
 冲刺阶段：一周
   计划：
   ·前端组跑通基本的jsp代码，学习基本的前端语法
   拟定学习计划：
第一节 HTML

1-静态页面展示
2-网站信息页面显示
3-网站图片显示
4-网站列表显示
5-网站首页显示
6-网站注册页面显示
7-后台页面的显示

第二节 CSS

1-CSS 的使用
2-CSS 总结
3-DIV+CSS完成注册页面布局

第三节 Javascript

1-js 的概述
2-注册页面数据的校验
3-js完成图片滚动效果
4-定时弹出广告
5-表单的提示和校验
6-表格的隔行变色
7-复选框的全选和全不选
8-省市联动效果

第四节 Jquery

1-jquery 概述
2-jQuery定时弹出广告
3-jQuery隔行变色
4-jQuery全选和全不选
5-jQuery省市联动
6-jQuery下拉列表左右选择
7-jQuery完成表单校验

第五节 BootStrap

1-BootStrap概述
2-BootStrap 栅格
3-BootStrap表单和按钮
4-BootStrap 组件
5-实现导航条和图片轮播
6-BootStrap 首页布局

   ·后端组学习Spring MVC框架，数据库部分
https://cloud.tencent.com/developer/article/1100074
目前xie学习的是java客户机服务器的模型，wang学习数据库的部分。
第六节 mysql

1-MySql概述
2-SQL 概述
3-数据库的增删改操作
4-数据库的查询
5-电子商城表的分析和设计
6-多表查询

第七节 JDBC

1-JDBC 概述
2-使用JDBC完成CRUD操作
3-在JDBC中使用连接池
4-使用元数据抽取DBUtils工具类

第八节 XML

1-xml概述
2-xml的组成
3-xml的解析
4-xml的约束

第九节服务器入门

1-tomcat 概述
2-tomcat 安装
3-tomcat发布web工程
4-Http协议
5-servlet入门
6-用户登陆案例-实现
7-用户登陆案例-总结
8-登陆后跳转
9-记录登陆次数

第十节 request和response

1-读取WEB工程下的文件
2-文件的下载
3-解决响应中文问题
4-用户注册

第十一节 COOKIE和session

1-会话技术概述
2-记录用户上次访问时间
3-记录用户商品浏览记录
4-session购物车的实现
5-验证码的校验

第十二节 jstl,el和jsp

1-jsp 概述
2-jsp 的注释和指令
3-jsp 的内置对象
4-pageContext对象
5-el 表达式
6-jstl 入门
7-jstl 常见标签的使用
8-将商品信息显示到页面上

第十三节 MVC和事务

1-jsp 的设计模式
2-反射回顾
3-内省
4-事务入门
5-转账案例
6-事务管理
7-案例总结
8-商品信息的添加和修改
9-商品信息删除和分页

第十四节 JQuery和AJax

1-Ajax 入门
2-Ajax 的请求
3-异步校验用户名是否存在
4-完成用户名的校验
5-模仿百度提示页面
6-Jquery完成省市联动（XML数据）
7-Jquery 完成省市联动（JSON数据）

第十五节 Listener和Filter

1-监听器概述
2-监听域对象销毁与创建
3-监听域对象属性的改变
4-监听session中javaBean状态的改变
5-过滤器入门
6-使用过滤器完成自动登陆
7-字符集编码过滤器

第十六节基础加强

1-自定义注解
2-servlet3.0 注解开发
3-Servlet3.0文件上传
4-动态代理-编码过滤器
5-动态代理-总结

  
  
学习心得：
wang:框架这个东西吧，有点抽象，然后好像往上套有点僵硬;我们主要就把结构理解了,而且，咱们的程序没那么大;至于说开发，大致上差不多就行了，多关注内容，不要被框架限制死了，不然可能效率不高;我今天看那本Javaweb开发，他就是强行解耦，搞一大堆.xml文件,反倒特别复杂
这不符合敏捷开发的思想。


环境一大堆的什么xml没搞懂，环境搭建不成功。
jsp、js不是特别理解。

=======================================================================================================================================
第一阶段的任务基本完成，制定第二周的任务：
对接前端。后端暂时没有问题，已经完成测试了
注意：
·xml不是用来写HTML的




