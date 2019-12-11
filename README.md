# 图书馆借阅系统

- forked from [MDN Django Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)
- 在前者基础上练习 Web 建站
- 熟悉并掌握 Server-Side Website 建站基础知识

## 技术栈

- Django (Python3)
- Django Rest Framework
- MySQL
- Bootstrap 4

## 设计思路

- 需求文档 / 功能列表 (Markdown)
- 原型设计 / UI 设计 (Photoshop/Illstrator)
- 开发 (PyCharm)
- 测试
- 部署 (Heroku)

## 功能

1. 登录
2. 首页
3. 图书

- 图书列表
- 图书 CRUD

4. 作者

- 作者列表
- 作者 CRUD

5. 个人信息

- 基本信息
- 借阅信息

## 开发笔记

1. 测试帐户

| 用户  | 密码     | 角色                  |
| ----- | -------- | --------------------- |
| robin | robin123 | 管理员 admin          |
| luffy | 123admin | 图书管理员 librarians |
| nami  | 123admin | 读者 library members  |

2. Todo List 

-[x] 侧边菜单栏 高亮选中项 (Menu)  
refs: [How to render menu with one active item with DRY?](https://stackoverflow.com/questions/9793576/how-to-render-menu-with-one-active-item-with-dry)  
-[ ] 面包屑 (Breadcrumb)  
refs: [How to implement breadcrumbs in a Django template?](https://stackoverflow.com/questions/826889/how-to-implement-breadcrumbs-in-a-django-template)  
-[ ] 列表分页 (Pagination)  
-[ ] 列表筛选 (Filter)  
-[ ] 图片上传，图片服务器 (Image Upload)  
-[ ] 提示窗口 (Alert)  
-[ ] 推送 (Push Notification)  
-[x] web 小图标 (favicon)  
-[ ] 表单样式及 value (Form)  
-[x] 时间选择 (Datetime Picker)  
refs: [Bootstrap Datepicker](https://github.com/uxsolutions/bootstrap-datepicker)  
-[ ] 撤销 (undo)  
-[ ] 删除 Model via Ajax  
refs: [Delete Model object in django Using jquery Ajax](https://stackoverflow.com/questions/40861518/delete-model-object-in-django-using-jquery-ajax)  
[Button in html that deletes an instance of a Django model](https://stackoverflow.com/questions/34234580/button-in-html-that-deletes-an-instance-of-a-django-model)
