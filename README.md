# 1.项目介绍
- 系统角色：管理员、普通用户
- 功能模块：管理员（用户管理、药品分类管理、药品信息管理、系统管理、订单管理等），普通用户（查看相关药品信息、充值、登录注册、个人中心、购物车、我的订单等）
- 技术选型：SSM，vue，uniapp等
- 测试环境：idea2024，HbuilderX，微信开发工具，Maven3，jdk1.8，mysql5.7等
# 2.项目部署
## 2.1 后端部署
- 创建数据库，导入sql
- 通过idea打开项目ssm39882，根据本地数据库环境配置src/main/resources/config.properties 3-5行
- 配置tomcat，Application context配置为/ssm39882，这个路径可以自行修改，如果修改注意要修改uniapp项目的请求url
- 后端管理web，基于Vue开发，路径为src/main/webapp/admin，你可以通过vscode或者webstorm等IDE工具进行修改，本项目的将编译后的dist直接放在tomcat运行
- 启动tomcat后，管理web：http://localhost:8080/ssm39882/admin/dist/index.html， 管理员账号密码：abo/abo
## 2.2 小程序部署
- 首先说明：压缩包内提供的mp-weixin是通过HbuilderX 编译后的，你可以直接通过微信开发工具打开，如果你想自己修改，请看下面的步骤
- 通过HbuilderX工具打开ssm39882下的src/main/webapp/front目录
- 修改mainfest.json里的uniapp应用标识和小程序的appid
- 运行到微信小程序即可，登录账号密码查看yonghu表，比如123/123
# 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.png)
![输入图片说明](3.png)
![输入图片说明](4.png)
![输入图片说明](5.png)
![输入图片说明](6.png)
![输入图片说明](7.png)
![输入图片说明](8.png)
![输入图片说明](9.png)
![输入图片说明](91.png)


# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)