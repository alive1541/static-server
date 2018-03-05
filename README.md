# static-server
一个基于node的静态文件服务器
# 功能
- 读取静态文件
- MIME类型支持
- 缓存支持/控制
- 支持gzip、defalte压缩
- Range支持，断点续传
- 全局安装
# 安装
- npm install static-server2 -g
# 启动服务
- server-start
# 配置
- 配置根目录：server-start -d /user/
- 配置根域名：server-start -o localhost
- 配置端口：server-start -p 8080
# 例子
- 在本机的9090端口上监听客户端的请求：server-start -d / -p 9090 -o localhost 