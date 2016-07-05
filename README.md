
# ~~高效~~专业界面设计之道

## 设计师工具

括号内的 M 表示改软件可在 Mac OS X 上运行, W 表示 Windows, 而 L 表示 Linux.

- [Zeplin]() (M)
- [SourceTree](https://www.sourcetreeapp.com/) (M W) Git 客户端界面工具

### 图像压缩与格式转换

- [ImageOptim](https://imageoptim.com/) (M) 图像压缩
- [ImageAlpha](https://pngmini.com/) (M) 有损 PNG 压缩
- [Pngyu](http://nukesaq88.github.io/Pngyu/)  (M) 有损 PNG 压缩
- [imagemin](https://github.com/imagemin/imagemin-app) (M W L) 图像压缩
- [XnConvert](http://www.xnview.com/en/xnconvert/) (M W L) 图像格式转换
- [HandBrake](https://handbrake.fr/) (M W L) 视频转码

### 命令行工具

部分命令行工具依赖某种语言环境，这些语言都有各自的包管理工具，例如基于 Node.js 开发的命令行工具，通常可以通过 `npm install <package>` 安装；基于 Python 开发的命令行工具，通常可以通过 `pip install <package>` 安装；基于 Ruby 开发的命令行工具，通常可以通过 `gem install <package>` 安装。这三种语言都是跨平台的，Mac OS X 上系统默认自带 Python 与 Ruby 开发环境，Windows 下可以使用 EXE 安装文件。

其它二进制包形式的命令行工具，Mac OS X 上可以通过 [Homebrew](http://brew.sh/) 或 [MacPorts](https://www.macports.org/) 安装。

- [PNGOUT](http://advsys.net/ken/utils.htm), [PNGCrush](http://pmt.sourceforge.net/pngcrush/) 无损 PNG 压缩
- [pngquant](https://pngquant.org/) 有损 PNG 压缩
- [SVGO](https://github.com/svg/svgo) (Node.js) SVG 优化工具
- [CairoSVG](http://cairosvg.org/) (Python) SVG 转 PNG, PDF, PostScript 工具
- [ImageMagick](http://www.imagemagick.org/), [GraphicsMagick](http://www.graphicsmagick.org/)  图片处理与格式转换
- [AutoTrace](http://autotrace.sourceforge.net/) 位图转矢量
- [Potrace](http://potrace.sourceforge.net) 位图转矢量, 仅支持单色

### 开发相关

- [FENIX](http://fenixwebserver.com/) (M W) 静态 Web 服务，可用于文件共享或静态网页演示。
- [Dash](https://kapeli.com/dash) (M), [Zeal](https://zealdocs.org/) (W) 编程语言参考文档

## 团队协作与流程

以下都是安装在服务器上的 Web 程序，如果团队或公司内部没有 Linux 服务器管理相关的技术人员，内部使用可以直接从 [Bitnami](https://bitnami.com/) 下载已配置好的虚拟机镜像或 Docker 镜像。

- [GitLab Community Edition](https://about.gitlab.com/downloads/) Git 服务器端 Web 程序，GitHub 的公司内部替代品，有丰富 API。
- [Owncloud](https://owncloud.org/)  服务器端的网盘程序
- [Rocket Chat](https://rocket.chat/) Slack 的替代品
- [Ghost](https://ghost.org/developers/) 极简的 Blog 程序

- Jekyll
- [Fabricator](http://fbrctr.github.io/) 

## 界面设计软件编程与自动化

### Adobe 软件脚本编程

- [Photoshop Scripting](http://www.adobe.com/devnet/photoshop/scripting.html) Photoshop 脚本编程
- [Illustrator Scripting](http://www.adobe.com/devnet/illustrator/scripting.html) Illustrator 脚本编程
- [ScriptUI for dummies](http://www.kahrel.plus.com/indesign/scriptui.html)  by Peter Kahrel. ScriptUI 教程.
- [xtools 2.2](http://sourceforge.net/projects/ps-scripts/files/xtools/v2.2/)  Photoshop 脚本开发工具
- [Creative Cloud Extension Builder for Brackets](http://davidderaedt.github.io/CC-Extension-Builder-for-Brackets/)  Brackets插件, 非官方的扩展开发工具

### Sketch 插件开发

- [Sketch Developer](http://developer.sketchapp.com/)  官方插件开发文档
- [Sketch Plugin Directory](https://github.com/sketchplugins/plugin-directory)  官方插件目录, 收集各种托管在 GitHub 的开源 Sketch 插件

### 教程

- [HTML panal 系列教程](http://www.davidebarranca.com/category/code/html-panels/) by Davide Barranca
- [Sketch Plugins Cookbook](https://github.com/turbobabr/Sketch-Plugins-Cookbook)

### 自动化编程

- [JavaScript for Automation](https://developer.apple.com/library/mac/releasenotes/InterapplicationCommunication/RN-JavaScriptForAutomation/) Mac OS X 10.10 JavaScript 自动化编程

## 免费素材

### 图标与图标字体

[Material Design Icons](https://github.com/google/material-design-icons)
[Font-Awesome](https://github.com/FortAwesome/Font-Awesome)
[Github octicons](https://github.com/github/octicons)
[ionicons](https://github.com/driftyco/ionicons)
[open-iconic](https://github.com/iconic/open-iconic)

### Emoji

[Noto emoji](https://github.com/googlei18n/noto-emoji)
[Twemoji](https://github.com/twitter/twemoji)
[Emoji One](https://github.com/Ranks/emojione)
[Mozilla Emoji](https://github.com/mozilla/fxemoji)

### 字体

[Google Fonts](https://github.com/google/fonts)
[Roboto](https://github.com/google/roboto)
[Noto fonts](https://github.com/googlei18n/noto-fonts)
[Noto CJK](https://github.com/googlei18n/noto-cjk)
[Adobe Source Han Sans](https://github.com/adobe-fonts/source-han-sans)
[Adobe Source Code Pro](https://github.com/adobe-fonts/source-code-pro)
[Adobe Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro)
[Adobe Source Serif Pro](https://github.com/adobe-fonts/source-serif-pro)
[Mozilla Fira](https://github.com/mozilla/Fira)
[Fira at Carrois](https://github.com/carrois/Fira-at-Carrois)
[FiraCode](https://github.com/tonsky/FiraCode)

### Image

[SubtlePatterns](https://github.com/subtlepatterns/SubtlePatterns)
