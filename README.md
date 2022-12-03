# springboot-login-log4j2

### 项目介绍

在laoyogd的[springboot-login](https://github.com/laoyog/springboot-login)项目的基础上引入了log4j2生成日志，作为复现CVE-2021-44228的靶场。

### docker一键部署

https://github.com/Ode1esse/springboot-login-log4j2-docker

### 本地调试

运行之后访问http://127.0.0.1:9090

![image-20211214205005122](resource/README/media/image-20211214205005122.png)

在登陆失败时会产生一条错误日志

![image-20211214205221675](resource/README/media/image-20211214205221675.png)

![image-20211214205341001](resource/README/media/image-20211214205341001.png)

### 参考链接
https://blog.csdn.net/byteArr/article/details/80955703

https://www.toutiao.com/i6843391272229536267

