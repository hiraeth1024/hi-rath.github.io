## docsify介绍

- Docsify即时生成您的文档网站。与 GitBook 不同，它不会生成静态 html 文件。相反，它会智能地加载和解析您的 Markdown 文件，并将它们显示为网站。



- docsify官方文档入口:[https://docsify.js.org/](https://docsify.js.org/)



## docsify安装及初始化

> step1:安装Node.js

搜索进入官网，点击下载，选择windows install (.msi) 64-bit

![](D:\图片\截图\Snipaste_2023-02-02_14-11-50.png)

> step2:安装docsify工具包

打开命令提示符`win+r`，输入`cmd`

输入`npm i docsify-cli -g`，推荐全局安装

![](D:\图片\截图\Snipaste_2023-02-02_14-28-38.png)



> step3:初始化

切换到想初始化的目录，输入`docsify init`进行初始化

![](D:\图片\截图\Snipaste_2023-02-02_14-36-57.png)

打开文件夹查看

![](D:\图片\截图\Snipaste_2023-02-02_14-37-17.png)



## 开始编写

### 准备工作

- 使用vs code打开docs目录

- 在终端中输入`docsify serve ./docs`运行本地服务器。可以在浏览器中预览网站

> 注意：要在上级文件夹中输入命令

![](D:\图片\截图\Snipaste_2023-02-02_14-46-55.png)



- 在`README.md`文件中输入`hello docsify`可以显示出表示成功！

![](D:\图片\截图\Snipaste_2023-02-02_15-30-44.png)

效果如下

![](D:\图片\截图\Snipaste_2023-02-02_15-28-39-1675323062903.png)

### 多页文档

- 如果您需要更多页面，只需在docsify目录中创建更多md文件即可。
- 在要实现跳转的md文件中，输入`[显示的名称](链接/文件)`

![](D:\图片\截图\Snipaste_2023-02-02_15-42-37.png)

在`more.md`中输入内容

![](D:\图片\截图\Snipaste_2023-02-02_15-44-25.png)

最终显示效果

![](D:\图片\截图\Snipaste_2023-02-02_15-45-22.png)

![](D:\图片\截图\Snipaste_2023-02-02_15-45-28.png)

