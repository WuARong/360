# 360

Gulp是基于Nodejs开发的一个构建工具。
#全局安装
npm install -g gulp
#本地安装（做为项目依赖）
在项目根目录下执行
npm install gulp --save-dev
#创建任务清单gulpfile.js
 
#定义任务
比如自动添加CSS私有前缀
本地安装gulp-autoprefixer --save-dev
 
#执行任务
输入命令 gulp
 
这样我们的CSS文件便会被自动的添加了浏览器私有前缀了
#	Gulp API
参见http://www.gulpjs.com.cn/docs/api/
5.2.3	常用Gulp插件
Gulp-uglify
Gulp-autoprefixer
Gulp-htmlmin
Gulp-less
Gulp-minify-css
Gulp-imagemin
Gulp-concat
gulp-rev
gulp-rev-collector
gulp-clean
#gulp插件库：
http://gulpjs.com/plugins/
