# helloWorld_goLang 安装go语言开发环境
## 一、安装VSCode编辑器
VSCode采用 JavaScript 技术，兼容几乎所有流行的操作系统，特别是对中文支持堪称完美！它不仅是跨平台多语言软件开发工具，而且是 Linux 平台写 Github Flavored Markdown 的神器
- 首先[下载](https://code.visualstudio.com/download)VSCode .rpm安装包
    - 因为CentOS是基于RPM的系统，所以需要下载rpm包，而非deb包（详细见[Linux下软件包的分类及deb、rpm、tar.gz的区别(https://blog.csdn.net/liu865033503/article/details/86014773)）
- 下载成功后在终端打开文件目录，输入以下命令自动安装
 ` rpm -ivh code-1.38.0-1567548134.el7.x86_64.rpm`
- 成功后在`应用程序`->`编程`中可以看到Visual Studio Code
    ![code](image/1.png)
