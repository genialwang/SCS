# SCS
SCS是一个简单的SOA系统，是国科大并行计算的课程作业之一。SCS包括两个部分，服务器以及客户端。
客户端使用Swing开发。服务器主要负责与MySQL交互返回请求结果。
## 课程作业要求
采用SOA的设计模式，设计一个分布式学生交流管理系统，并在实际的软件环境中编程、测试、部署面向服务的软件。具体要求如下：
 - 以基于SOAP协议的服务形式完成学生交流管理系统的设计与开发。系统开发要求使用JAVA语言，Mysql数据库，服务器端采用Tomcat服务器，使用Axis2作为WebService容器。[注]可以选择其它语言编程，但要符合Web服务的标准。
 - 系统设计实现文档要求包括对需求的分析，系统服务库的设计，各个具体服务的WSDL描述文件及解释，Axis2界面中注册服务列表的截图，系统的相关页面截图，各个功能结果的截图。
 - 最终要求提交系统设计实现文档记录与系统程序安装包。要求系统打包为.war格式，直接可放入Tomcat中运行，数据库文件保存为脚本，可在Mysql中运行创建。

## 主要功能
 - 用户注册：系统提供注册界面进行用户注册，注册内容包括登录名，密码，姓名。
 - 登录/注销：用户可使用已注册的登录名和密码进行登录，登录后进入主页面。
 - 内容发布：每个注册用户可以进行内容发布，发布的内容包含标题和正文。
 - 内容列表：用户登录后，可查看自己与其他用户发布的所有内容列表，列表中显示该条内容的标题和详情，并显示发布者信息。
 - 内容删除：在内容列表中，用户可对自己发布的内容进行删除操作。
