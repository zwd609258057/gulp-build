alt	React的Flux实现
async	异步流程控制
babel	ES6转换为ES5
body-parser	渲染POST请求数据
colors	美化控制台输出结果
compression	Gzip压缩
express	Node.js Web框架
mongoose	MongoDB ODM
morgan	HTTP请求日志
react	React框架
react-router	React路由库
request	HTTP请求库
serve-favicon	提供favicon.png
socket.io	显示有多少用户在线
swig	渲染HTML
underscore	JS辅助库
xml2js	将XML渲染为JSON


Gulp Task	Description
vendor	将所有第三方JS文件合并到一个文件
browserify-vendor	因为性能原因，我们将NPM模块和前端模块分开编译和打包，因此每次重新编译将会快个几百毫秒
browserify	仅将app文件编译并打包，不包括其它模块和库
browserify-watch	包括上面的功能，并且监听文件改变，然后重新编译打包app文件
watch	当文件改变时重新编译LESS文件
default	运行上面所有任务并开始监听文件改变
build	运行上面所有任务然后退出
