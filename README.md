## 团队协作

### 项目管理

这些程序通常为开发者所使用和熟知，它们引入一种更为现代和高效的工作方式，这些方法适合任何软件工作者，包括设计师。这些程序提供了非常完整的项目管理的一系列功能，诸如文件管理（包括备份、同步、历史记录、评审等），成员管理（权限控制等），问题跟踪（可用于任务计划、Bug 跟踪等），文档（用于备注、帮助、规范等）等等。如果设计师需要与开发人员能够更顺畅地沟通和协作，学习和使用这类程序是非常必要的。

以下为可自托管得免费开源 Web 应用程序。安装与配置请咨询有 Linux 服务器管理经验的技术人员，内部可以直接使用已配置好的虚拟机镜像或 Docker 镜像。

- [GitLab Community Edition](https://about.gitlab.com/downloads/) (Linux) Git 服务器端 Web 程序，GitHub 的替代品，功能强大。
- [Gogs](https://gogs.io/) (全平台) 国产 Git 服务器端 Web 程序，安装简单，多语言界面，跨平台。当团队或公司中没有技术支持时，这个程序是不错的选择。
- [Gitea](https://gitea.io) Gogs 衍生版。

免费和付费在线托管。

- [GitHub](https://github.com/) 免费项目的内容是开放的，私密项目需要付费。
- [GitLab](https://gitlab.com/) 免费用户有部分高级功能限制。
- [BitBucket](https://bitbucket.org/) 免费用户有团队人数限制。

### 文件共享

很多公司不允许使用外部网盘，但日常工作中又需要大文件传输，如果有自己的网盘程序，就可以方便的共享文件和备份文件。

以下是针对公司内部使用而设计的自托管的网盘程序，包括 Web、iOS、Android 平台客户端，借助桌面的客户端可以实现多台电脑间的文件同步。

- [Owncloud](https://owncloud.org/) (PHP + MySQL/PostgreSQL)，成员是由管理员添加并分配权限的，可以全局搜索文件，对文件评论和简单的历史版本，可以安装一些插件形式的应用来扩展类似日程、任务、文档等功能。
- [NextCloud](https://nextcloud.com/) Owncloud 衍生版。

### 即时通讯

以下是自托管的 Slack 的开源替代品，包括 Web、iOS、Android 平台客户端。

- [Rocket Chat](https://rocket.chat/) (Node.js)
- [Mattermost Team Edition](https://about.mattermost.com/download/) (Go)
- [Gitter](https://gitlab.com/gitlab-org/gitter/) (Node.js)

免费和付费在线服务。

- [Slack](https://slack.com/) 免费用户有存储空间（5G）、应用（10）、信息历史（10k）等限制。
- [Stride](https://www.stride.com/) 免费用户有存储空间（5G）、应用（10）、信息历史（25k）等限制。
- [Gitter](https://gitter.im/) 无限制。

### 文档、知识共享

静态站点生成器，使用某种编程环境将 Markdown、reStructuredText 等文件生成网页形式的文档，适用于内部设计规范，技术文档等等。样式的可定制比较强，大部分程序在初始化时，并不带任何主题，这类工具需要基础的命令行操作知识，网站部署知识，甚至是一些 HTML、CSS 等知识，其实大部分静态站点生成器都可以从网上找不到不少模版。

- [Jekyll](http://jekyllrb.com/) (Ruby) Github Pages 所使用的静态网站生成程序。
- [GitBook](https://github.com/GitbookIO) (Node.js) 文档类静态网站生成程序。
- [Hugo](http://gohugo.io/) (Go)
- [Hexo](https://hexo.io/) (Node.js)

静态站点生成器中有一类不需要特殊编程环境来转化文件，直接在浏览器上将 Markdown 渲染成 HTML，只需要简单配置目录结构便可快速实现一个文档网站。

- [MDwiki](https://github.com/Dynalon/mdwiki/)
- [Docsify](https://github.com/QingWei-Li/docsify)

免费和付费在线服务。

- [Nition](https://www.notion.so/)
- [Quip](https://quip.com/)

## 设计团队相关

### Sketch 生态圈

- **版本控制**
  - [Abstract](https://www.goabstract.com/)
  - [Plant](https://projects.plantapp.io/)
- **Developer Handoff**
  - [Zeplin](https://zeplin.io/)
  - [Sympli](https://sympli.io/)
  - [AvoCode](https://avocode.com/)
  - [Sketch Measure](https://github.com/utom/sketch-measure)

------

## 界面设计软件编程

### Sketch 插件开发

- [Sketch 官方插件开发文档](http://developer.sketchapp.com/)
- [Sketch API 源码](https://github.com/BohemianCoding/SketchAPI)和[文档](https://developer.sketchapp.com/reference/api/)
- [Sketch Headers](https://github.com/abynim/Sketch-Headers) Headers from Sketch app exported using class-dump
- [Sketch 官方插件目录](https://sketchapp.com/extensions/plugins/)
- [Sketch 官方开发者论坛](http://sketchplugins.com/) 

### Figma API

- [Figma API](https://www.figma.com/developers)

### Adobe 系列软件编程

- Photoshop 脚本编程 [Photoshop Scripting 官方文档](http://www.adobe.com/devnet/photoshop/scripting.html)
- Illustrator 脚本编程 [Illustrator Scripting 官方文档](http://www.adobe.com/devnet/illustrator/scripting.html)
- After Effects 脚本编程 [aescripts + aeplugins](https://aescripts.com/), [After Effects Scripting Guide](http://docs.aenhancers.com/)
- [ScriptUI for dummies](http://www.kahrel.plus.com/indesign/scriptui.html)  by Peter Kahrel. ScriptUI 教程.
- [xtools 2.2](http://sourceforge.net/projects/ps-scripts/files/xtools/v2.2/)  Photoshop 脚本开发工具
- [Creative Cloud Extension Builder for Brackets](http://davidderaedt.github.io/CC-Extension-Builder-for-Brackets/)  Brackets插件, 非官方的扩展开发工具
- [HTML panal 系列教程](http://www.davidebarranca.com/category/code/html-panels/) by Davide Barranca

------

## 命令行工具与 Shell 编程

### 命令行工具

macOS 系统建议安装 [oh-my-zsh](http://ohmyz.sh/)，Windows 可以使用 [Cygwin](http://www.sourceware.org/cygwin/) 模拟 Linux/Unix 的 Shell 环境。

大部分命令行工具，在 macOS 上可以通过 [Homebrew](http://brew.sh/) 安装。

- [PNGOUT](http://advsys.net/ken/utils.htm), [PNGCrush](http://pmt.sourceforge.net/pngcrush/), [OptiPNG](http://optipng.sourceforge.net/) 无损 PNG 压缩
- [pngquant](https://pngquant.org/) 有损 PNG 压缩
- [FFmpeg](http://ffmpeg.org/) 视频工具
- [Gifsicle](http://www.lcdf.org/gifsicle/) Gif 工具
- [CairoSVG](http://cairosvg.org/) SVG 转 PNG, PDF, PostScript 工具
- [ImageMagick](http://www.imagemagick.org/) 图片处理与格式转换
- [AutoTrace](http://autotrace.sourceforge.net/) 位图转矢量
- [Potrace](http://potrace.sourceforge.net) 位图转矢量, 仅支持单色

### Shell 编程

- [Shell Scripting Primer](https://developer.apple.com/library/mac/documentation/OpenSource/Conceptual/ShellScripting/shell_scripts/shell_scripts.html) by Apple
- [Creating Shell Script Actions for Automator](https://developer.apple.com/library/content/documentation/AppleApplications/Conceptual/AutomatorConcepts/Articles/ShellScriptActions.html#//apple_ref/doc/uid/TP40002078-BCIBAEAC) by Apple
- [Bash 速记表](https://devhints.io/bash)

------

## 图像编程

### Node.js

[包管理](https://www.npmjs.com/)

- [gulp](http://gulpjs.com/) 自动构建工具
- [SVGO](https://github.com/svg/svgo) SVG 优化工具
- [SVG font dumper](https://github.com/fontello/svg-font-dump) SVG 字体转为多个 SVG 图片
- [node-canvas](https://github.com/Automattic/node-canvas)
- [Jimp](https://github.com/oliver-moran/jimp) 图像处理

### Python

[包管理](https://pypi.python.org/pypi)

- [Pillow](http://pillow.readthedocs.io/en/latest/)
- [Wand](http://docs.wand-py.org/)

## 其他

- [Cairo](https://www.cairographics.org/)