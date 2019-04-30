# 前端

![avater](view/登陆.png)  

![avater](view/主页.png)  

![avater](view/标签.png)  

![avater](view/个人界面.png)

# 后端

* ## **整体流程**  
![avater](流程.jpg)

* ## **RESTful API**   
>  一种软件架构风格、设计风格，而不是标准，只是提供了一组设计原则和约束条件。
![avater](服务端API.png)

* ## **一些问题**
    ### **1.Token**
    * 为什么要生成Token?
    * 项目生成Token的方法
        >服务器生成一个密钥，使用HS256对客户端信息进行加密生成Token，并将生成的Token返回给客户端，客户端之后每次访问服务端都携带此Token，服务端解析Token得到用户的相关信息。
        ![avater](GetToken.png)
    ### **2.数据库设计**