# node + express + mongodb blog demo

## mongodb 安装
下载：https://www.mongodb.com/download-center  
文档：http://www.mongodb.org.cn/tutorial/55.html   
adminMongo： https://adminmongo.markmoffat.com/docs/#Setting%20a%20context%20path

## 功能分析  
搭建一个简单的具有多人注册、登录、发表文章、登出功能的博客。

## 设计目标  
未登录：主页左侧导航显示 home、login、register，右侧显示已发表的文章、发表日期及作者。 登陆后：主页左侧导航显示 home、post、logout，右侧显示已发表的文章、发表日期及作者。 用户登录、注册、发表成功以及登出后都返回到主页。

启动：  
adminMongo:  npm run dev  (mongodb://127.0.0.1:27017)  
mongodb: mongod --dbpath "f:\data\db"  

npm install  
npm start

链接：  
http://wiki.jikexueyuan.com/project/express-mongodb-setup-blog/simple-blog.html
