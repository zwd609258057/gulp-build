1. alt	React的Flux实现
2. async	异步流程控制
3. babel	ES6转换为ES5
4. body-parser	渲染POST请求数据
5. colors	美化控制台输出结果
6. compression	Gzip压缩
7. express	Node.js Web框架
8. mongoose	MongoDB ODM
9. morgan	HTTP请求日志
10. react	React框架
11. react-router	React路由库
12 .request	HTTP请求库
13. serve-favicon	提供favicon.png
14. socket.io	显示有多少用户在线
15. swig	渲染HTML
16. underscore	JS辅助库
17. xml2js	将XML渲染为JSON


#### Gulp Task	Description
1. vendor	将所有第三方JS文件合并到一个文件
2. browserify-vendor	因为性能原因，我们将NPM模块和前端模块分开编译和打包，因此每次重新编译将会快个几百毫秒
3 .browserify	仅将app文件编译并打包，不包括其它模块和库
4. browserify-watch	包括上面的功能，并且监听文件改变，然后重新编译打包app文件
5. watch	当文件改变时重新编译LESS文件
6. default	运行上面所有任务并开始监听文件改变
7. build	运行上面所有任务然后退出
