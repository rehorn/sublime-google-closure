Google Closure JS Compiler for Sublime Text 2 本地版简介
========================

------------------------
Google Closure JS Compiler for Sublime Text 2 是代码编辑器 Sublime Text 2 的一个 JavaScript 编译插件，能够对 JavaScript 文件进行压缩，生成用于生产环境的 .min.js 文件。

安装
------------------------
* 方式1
    * 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
    * 在Packages目录本代码仓库，Git Clone https://github.com/rehorn/sublime-google-closure
    * 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件
* 方式2
    * 安装 Packages Control 后，将本代码仓库添加到源
        * ctrl+alt+p之后，输入add repository，输入 https://github.com/rehorn/sublime-google-closure
    * 执行 Packages Control 后，就能搜索到 sublime-google-closure ，安装即可
    * 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件

使用
------------------------
* 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件

自定义
------------------------
* 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
* 进入 sublime-google-closure
* 修改 Google Closure.sublime-build 文件，可以自定义编译目录，文件名等
* 可替换 complier/compiler.jar 升级Google Closure

其他
------------------------

