# 说明
这是一个vue自带demo的打包练习项目，旨在熟悉打包流程。

流程
1、新建项目vue_test
2、settings中设置GitHub Pages Source 的master branch
3、进入本地vue项目目录，cmd输入npm run build打包项目(生成到dist文件夹)
4、提交dist中的文件到vue_test分支中
5、打开首页 https://frank2088.github.io/vue_test/index.html

注意：
打包前可以打开config文件夹下的index.js
设置productionSourceMap为false，这样js和css文件夹下不会生成.map文件。
设置assetsPublicPath为"./",这样本地打开也可以直接加载显示，没有路径错误。
