# <del>Validator</del>

此项目已经停止更新，改用：https://github.com/devefx/validator-web

---------------------------------------

Validator的特性：

* 前后端验证框架，设计精巧、使用简单
* 遵循OCP原则，强大的扩展性
* 支持SpringMVC、Struts2、Servlet
* 自动生成JavaScript前端验证代码
* 将Validate与Controller分离
* 统一验证规范
* 支持自定义验证规则

使用教程：

&nbsp;&nbsp;&nbsp;&nbsp;第一篇：<a href="http://blog.csdn.net/devefx/article/details/51565139" target="_blank">使用Validator做SpringMVC的验证框架 - 配置SpringMVC环境</a><br/>
&nbsp;&nbsp;&nbsp;&nbsp;第二篇：<a href="http://blog.csdn.net/devefx/article/details/51567533" target="_blank">使用Validator做SpringMVC的验证框架 - 使用Validator</a><br/>
&nbsp;&nbsp;&nbsp;&nbsp;第三篇：<a href="http://blog.csdn.net/devefx/article/details/51576672" target="_blank">使用Validator做SpringMVC的验证框架 - Validator前端验证</a><br/>
&nbsp;&nbsp;&nbsp;&nbsp;第四篇：<a href="http://blog.csdn.net/devefx/article/details/51595671" target="_blank">使用Validator做SpringMVC的验证框架 - 自定义验证组件</a><br/>

教程源码：<a href="http://download.csdn.net/detail/devefx/9542650" target="_blank">下载地址</a>

#更新日志

- 2017/02/16  修复缓存被JVM回收后未重新生成导致的异常
- 2016/12/20  增加AsyncFieldValidator抽象，通过继承此类自动实现前后台交互验证功能；增加组件OnlyBackValidator、OnlyFrontValidator；提升Cache利用
- 2016/09/19	  支持Class验证器（原仅支持方法验证），支持多个验证器
- 2016/09/05  增加对原始Servlet的验证支持
- 2016/06/28  修复Cache弱引用对象被GC回收导致NullPoint异常
