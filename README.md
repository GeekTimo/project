# project
社交网络程序

#前端项目#

1.client/dist文件是已经压缩过的前端文件

  主要包括了登录页面/注册页面/编辑个人基本信息板块/开发者信息板块/留言板块
  
2.client/common文件夹

  该文件夹下的各个组件主要是抽离了个人信息表单组件,以便于组件复用
  
3.util下的http.js文件

  封装axios和进行响应拦截的请求
  
4.验证

登录/注册/修改个人信息都依赖于后端传给前端的token进行验证处理


#后端项目#

1.后端框架express

2.认证依赖于jsonwebtoken模块,passport/passport-jwt模块以及validator模块

3.validatoion文件

  主要是各个组件的验证,例如:邮箱验证,密码验证,字符串限制等

4.models文件

    mongoose数据库的数据模型
    
5.routes/api文件
  
  该文件下主要是这个项目的后端接口,其中涉及有登录注册/个人信息/点赞留言等接口
  
