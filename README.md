# StudyJS
This just a demo for my Web-Front Study!  
And for now ,only used for testing GITHUB exercises.

## Study Vue.JS
参考Vue.js官方教程逐步实现摸索 Vue.js框架，并把学习的记录发上来  

为了美化demo，并练习Bootstrap,所有实例均采用[Bootstrap](https://github.com/twbs/bootstrap)样式

- [startVueJS.html](VueJS/Introduction/startVueJS.html)  VueJS简单的演示  
- [SimpleTodoDemo.html](VueJS/Introduction/SimpleTodoDemo.html)    简单的Todo Demo

---
上述示例使用的是vueJs1.0版本，后面切换到2.0版本    
### 介绍 Introduction
- [declarativeRendering.html](VueJS/Introduction/declarativeRendering.html) 声明式渲染演示demo  
- [Conditionals&Loops.html](VueJS/Introduction/conditionals&Loops.html) 条件和循环demo  
- [UserInput.html](VueJS/Introduction/UserInput.html) 用户输入内容处理和双向绑定  
- [components.html](VueJS/Introduction/components.html) 组件

### Vue 实例 The Vue Instance  
- [Constructor.html](VueJS/VueInstance/Constructor.html) 构造器  
- [Properties&Methods.html](VueJS/VueInstance/Properties&Methods.html) 属性与方法
- [LifecycleHooks.html](VueJS/VueInstance/LifecycleHooks.html) 生命周期

### 模板语法 Template Syntax

## Some command for Github:
```
//创建GIT目录对当前项目进行管理
$ git init      

//从Github上克隆一个仓库
$ git clone git@github.com:raphaelli/StudyJS.git

//检查仓库状态
$ git status

//跟踪新文件
$ git add   

//跟踪所有文件
$ git add .

//提交文件
$ git commit -m"本次提交说明"

//文件（夹）改名
$git mv file_from file_to

//查看日志
$ git log

//修改还未push到远程仓库的commit  :wq 保存并退出vi  q: 不报错退出vi
$ git commit --amend

//添加远程仓库  yourName & yourRepo 参见github或Kelude.code 的Id和项目名
$ git remote add origin git@github.com:yourName/yourRepo.git

//从远程仓库抓取数据
$ git fetch [remote-name]
$ git pull

//推送内容到远程仓库  异常时可以 -f 强制推送
//非个人项目最好不用(或者将项目全部fetch到本地，然后-f提交)
$ git push origin master

//查看远程仓库信息
$ git remote show git

//版本回退
$ git reset --hard HEAD^  //回退上一版本

$ git reset --hard 3628164  //回退制定版本(版本号)


```
