# 高效界面设计之道

括号内的 M 表示改软件可在 macOS 上运行, W 表示 Windows, 而 L 表示 Linux.

## 团队

### 工作方式

免费开源 Web 应用程序。

如果团队或公司内部没有 Linux 服务器管理相关的技术人员，可以直接从 [Bitnami](https://bitnami.com/) 下载已配置好的虚拟机镜像或 Docker 镜像用于内部使用。

- [GitLab Community Edition](https://about.gitlab.com/downloads/) Git 服务器端 Web 程序，GitHub 的替代品，有丰富 API，可扩展性强。
- [Gogs](https://gogs.io/) 国产 Git 服务器端 Web 程序，安装简单，多语言界面，跨平台。当团队或公司中没有技术支持时，这个程序是不错的选择。
- [Owncloud](https://owncloud.org/)  网盘程序。
- [Rocket Chat](https://rocket.chat/) Slack 的开源替代品。超越各种内部X信，XX通，大公司套路深...

### 协作和共享

- [SourceTree](https://www.sourcetreeapp.com/) Git 客户端界面工具。 (M W)
- [FENIX](http://fenixwebserver.com/) 静态 Web 服务，可用于内网的文件共享或静态网页演示。(M W)

### 知识共享

静态站点生成器，生成网页形式的文档，适用于内部设计规范，技术文档等等。需要基础命令行操作知识，网站部署知识，以及熟悉 Markdown 语法。

- [Jekyll](http://jekyllrb.com/) Github 使用的静态网站生成程序。
- [GitBook](https://github.com/GitbookIO) 文档类静态网站生成程序。

## 设计师工具

### 图像压缩与格式转换

- [ImageOptim](https://imageoptim.com/) 图像压缩 (M)
- [ImageAlpha](https://pngmini.com/) 有损 PNG 压缩 (M)
- [Pngyu](http://nukesaq88.github.io/Pngyu/) 有损 PNG 压缩  (M)
- [imagemin](https://github.com/imagemin/imagemin-app) 图像压缩 (M W L)
- [XnConvert](http://www.xnview.com/en/xnconvert/) 图像格式转换 (M W L)
- [HandBrake](https://handbrake.fr/) 视频转码 (M W L)

### 开发相关

- [Atom](https://atom.io/) 编辑器
- [Dash](https://kapeli.com/dash)  (M), [Zeal](https://zealdocs.org/) (W) 编程语言参考文档。 

### 命令行工具

部分命令行工具依赖某种语言环境，这些语言都有各自的包管理工具，例如基于 Node.js 开发的命令行工具，通常可以通过 `npm install <package>` 安装；基于 Python 开发的命令行工具，通常可以通过 `pip install <package>` 安装；基于 Ruby 开发的命令行工具，通常可以通过 `gem install <package>` 安装。这三种语言都是跨平台的，Mac OS X 上系统默认自带 Python 与 Ruby 开发环境，Windows 下可以使用 EXE 安装文件。

其它二进制包形式的命令行工具，Mac OS X 上可以通过 [Homebrew](http://brew.sh/) 或 [MacPorts](https://www.macports.org/) 安装。

- [PNGOUT](http://advsys.net/ken/utils.htm), [PNGCrush](http://pmt.sourceforge.net/pngcrush/), [OptiPNG](http://optipng.sourceforge.net/) 无损 PNG 压缩
- [pngquant](https://pngquant.org/) 有损 PNG 压缩
- [FFmpeg](http://ffmpeg.org/) 视频工具
- [Gifsicle](http://www.lcdf.org/gifsicle/) Gif 工具
- [SVGO](https://github.com/svg/svgo) SVG 优化工具 (Node.js)
- [CairoSVG](http://cairosvg.org/) SVG 转 PNG, PDF, PostScript 工具 (Python)
- [ImageMagick](http://www.imagemagick.org/), [GraphicsMagick](http://www.graphicsmagick.org/)  图片处理与格式转换
- [AutoTrace](http://autotrace.sourceforge.net/) 位图转矢量, [Potrace](http://potrace.sourceforge.net) 位图转矢量, 仅支持单色

### 包、模块

带有某种功能的代码，需要有特定语言的基础才能用其来完成特定操作，开发语言备注在说明后的括号内。

- [gulp](http://gulpjs.com/) 自动构建工具 (Node.js)
- [grunt](http://gruntjs.com/) 自动构建工具 (Node.js)
- [imagetracerjs](https://github.com/jankovicsandras/imagetracerjs) 位图转矢量 (Node.js)
- [SVG font dumper](https://github.com/fontello/svg-font-dump) SVG 字体转为多个 SVG 图片 (Node.js)

## 界面设计软件自动化编程

### Adobe 软件脚本编程

- [Photoshop Scripting](http://www.adobe.com/devnet/photoshop/scripting.html) Photoshop 脚本编程
- [Illustrator Scripting](http://www.adobe.com/devnet/illustrator/scripting.html) Illustrator 脚本编程
- [ScriptUI for dummies](http://www.kahrel.plus.com/indesign/scriptui.html)  by Peter Kahrel. ScriptUI 教程.
- [xtools 2.2](http://sourceforge.net/projects/ps-scripts/files/xtools/v2.2/)  Photoshop 脚本开发工具
- [Creative Cloud Extension Builder for Brackets](http://davidderaedt.github.io/CC-Extension-Builder-for-Brackets/)  Brackets插件, 非官方的扩展开发工具
- [HTML panal 系列教程](http://www.davidebarranca.com/category/code/html-panels/) by Davide Barranca

### Sketch 插件开发

- [Sketch Developer](http://developer.sketchapp.com/)  官方插件开发文档
- [SketchAPI](https://github.com/BohemianCoding/SketchAPI) Javascript API for working with Sketch
- [Sketch Headers](https://github.com/abynim/Sketch-Headers) Headers from Sketch app exported using class-dump
- [Sketch Plugin Directory](https://github.com/sketchplugins/plugin-directory)  官方插件目录, 收集各种托管在 GitHub 的开源 Sketch 插件

## 系统自动化编程

### macOS JavaScript for Automation

- [JavaScript for Automation](https://developer.apple.com/library/mac/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/) Mac OS X 10.10 JavaScript 自动化编程
- [JXA Cookbook](https://github.com/dtinth/JXA-Cookbook)

### Shell 编程

- [Shell Scripting Primer](https://developer.apple.com/library/mac/documentation/OpenSource/Conceptual/ShellScripting/shell_scripts/shell_scripts.html) by Apple
- [Linux Shell Scripting Tutorial](https://bash.cyberciti.biz/guide/Main_Page)
- [Unix Shell](http://www.tutorialspoint.com/unix/unix-shell.htm)
- [Advanced Bash-Scripting Guide - An in-depth exploration of the art of shell scripting](http://tldp.org/LDP/abs/html/) by Mendel Cooper

## 免费素材

### 图标与图标字体

- [Material Design Icons](https://github.com/google/material-design-icons) (Font, PNG, SVG)
- [Font-Awesome](https://github.com/FortAwesome/Font-Awesome) (Font)
- [Evil Icons](https://github.com/outpunk/evil-icons) (SVG, Ai, Sketch)
- [Elusive Iconfont](https://github.com/reduxframework/elusive-iconfont)  (Font, SVG)
- [Github octicons](https://github.com/github/octicons) (SVG, Sketch)
- [ionicons](https://github.com/driftyco/ionicons) (Font, PNG, SVG)
- [open-iconic](https://github.com/iconic/open-iconic) (Font, PNG, SVG, WebP)
- [Weather Icons](https://github.com/erikflowers/weather-icons) 天气图标 (Ai, Font)
- [Meteocons](http://www.alessioatzeni.com/meteocons/) 天气图标 (Font, PSD, CSH, EPS, SVG)
- [Map Icons](https://github.com/scottdejonge/map-icons) 地理图标 (Font, SVG)
- [Maki](https://www.mapbox.com/maki-icons/) 地理图标 (SVG)
- [Entypo](https://github.com/danielbruce/entypo) (Font, SVG)
- [awesome-uni.font](https://github.com/fontello/awesome-uni.font)  (Font, SVG)
- [typicons.font](https://github.com/stephenhutchings/typicons.font) (Font, PNG, SVG)
- [brandico.font](https://github.com/fontello/brandico.font) SNS 图标 (Font, SVG)
- [zocial.font](https://github.com/fontello/zocial.font)  (Font, SVG)
- [websymbols-uni.font](https://github.com/fontello/websymbols-uni.font)  (Font, SVG)
- [modernpics.font](https://github.com/fontello/modernpics.font)  (Font, SVG)
- [mfglabs.font](https://github.com/fontello/mfglabs.font)  (Font, SVG)

### Emoji

- [Noto emoji](https://github.com/googlei18n/noto-emoji) (Font, SVG, PNG 128px)
- [Twemoji](https://github.com/twitter/twemoji) (Ai, SVG, PNG 16,36,72px)
- [Emoji One](https://github.com/Ranks/emojione) (Font, SVG, PNG 64,128,512px)
- [Mozilla Emoji](https://github.com/mozilla/fxemoji) (Font, SVG)

### 字体

[Google Fonts](https://github.com/google/fonts),
[Noto fonts](https://github.com/googlei18n/noto-fonts),
[Noto CJK](https://github.com/googlei18n/noto-cjk),
[Adobe Source Han Sans 思源黑体](https://github.com/adobe-fonts/source-han-sans),
[Source Code Pro](https://github.com/adobe-fonts/source-code-pro),
[Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro),
[Source Serif Pro](https://github.com/adobe-fonts/source-serif-pro),
[Fira](https://github.com/mozilla/Fira),
[FiraCode](https://github.com/tonsky/FiraCode)

### 免费版权高清图片

[unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/)