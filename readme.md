# 1709A 同城帮项目练习

## 技术栈： Bootstrap + jQuery + Less + baiduTemplate + gulp + Node.js + Express + Mysql + 高德地图

 -----------------------------------------
## 创建过程
1. 新建一个目录 1709a_tcb
2. cd 1709a_tcb/
3. 在1709_tcb 内执行  git init
4. 在仓库内 新建 readme.md 文件，即本文件
5. 再新建一个 .gitignore 文件，编辑文件 ,内容写上 node_modules,之后有什么不需要上传的文件，都写在这个文件中
6. git add .  把当前目录下，所有未在.gitignore 中配置的文件添加到git中
7. git commit -m '注释内容'
8. 在github上新建一个远程仓库
9. 把本地仓库和远程仓库关联   git remote add origin 仓库地址
10. git push -u origin master

11. npm init 初始化npm
12. npm install --save jquery
13. npm install --save bootstrap
14. npm install --save-dev gulp 安装 gulp
15. 新建gulpfile.js
16. 安装gulp 插件
- del 删除目录
- gulp-less 编译less
- gulp-minify-css 压缩css
- gulp-uglify  压缩 js
- gulp-imagemin 压缩图片
- gulp-rename 重命名
- gulp-concat 文件合并
- gulp-livereload 浏览器自动刷新

---------------------------------------------

## 目录结构
	|- node_modules
	|- app
		|- html
		|- js
		|- less
		|- images
	|- dist
		|- html
		|- js
		|- css
		|- images
	|- lib
	|- gulpfile.js
	|- package.json
	|- readme.md

---------------------------------------------

# 如何使用

1. 把项目克隆下来  git clone https://github.com/cooleye/1709A_tcb.git
2. cd 1709A_tcb   (进入项目)
3. npm install	 （安装依赖）
4. npm run build  （执行打包命令）
5. npm run watch   （开启监听）

