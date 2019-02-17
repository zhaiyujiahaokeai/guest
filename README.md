# 基于Django的发布会签到系统
## 已实现功能：
###  1.登录
    请求方式：POST
    处理登录请求：通过form表单的action属性<form method="post" action="/login_action/">来指定提交的路径
    机制：Session
    引用django认证登录（admin后台）
    加@login_required避免未登录也能访问登录成功页面
  
