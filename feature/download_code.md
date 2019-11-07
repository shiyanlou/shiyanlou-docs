# 下载代码

## 介绍

实验环境中的代码文件如果需要拷贝出来，目前有几种办法：

1. 直接提交到 github
2. 使用下载代码功能

下载代码功能可以在图形界面和字符界面的右边工具栏看到，点击 `下载代码` 按钮后会有弹出框进行引导操作。

## 使用

将需要下载的文件复制或者移动到 `/home/shiyanlou/Code` 目录：

![mvtoCode](https://doc.shiyanlou.com/shiyanlou-docs/images/mvtoCode.jpg)

点击学习界面工具栏的 `下载代码` 按钮，将会将实验环境中的 `/home/shiyanlou/Code` 目录打包下载，可以将代码等需要导出环境的文件放到这个目录下。

![downloadcode](https://doc.shiyanlou.com/shiyanlou-docs/images/downloadcode.jpg)

代码下载会打开新的窗口，浏览器有可能把窗口拦截了，请查看浏览器地址栏右边是否有提示。另外下载代码限制最大为 5M，如果 `/home/shiyanlou/Code` 太大，会导致后台传输超时。

下载的代码会被打包成 tar 包，下载后在 Mac 和 Windows 上都可以通过常用的解压软件，例如 7zip 进行解压，在 Linux 上可以使用 tar 命令解压。

### Web IDE

在 Web IDE 中如果需要下载代码，只需要选中要下载的文件夹或者代码文件，右键选择 Download，就可以下载到本地。下载的代码会被打包成 tar 包，下载后在 Mac 和 Windows 上都可以通过常用的解压软件，例如 7zip 进行解压，在 Linux 上可以使用 tar 命令解压。

![webidedownload](https://doc.shiyanlou.com/shiyanlou-docs/images/webidedownload.jpg)

## 支持的界面

* [图形界面](../feature/desktop.md)
* [字符界面](../feature/terminal.md)
* [Web IDE](../feature/webide.md)

