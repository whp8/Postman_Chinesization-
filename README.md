# PostmanCn
最新中文版本：9.0.5  
更新时间：2021-10-05  
不要Clone存储库！  
请按照下面步骤：

## 步骤
1. [**下载&安装Postman**](#1下载安装postman)
2. [**安装中文包**](#2安装中文包)  
   　[**Windows**](#Windows)  
      　[**Mac**](#Mac)  
      　[**Linux**](#Linux)

## 帮助
[Postman官方文档](https://learning.postman.com/docs)  
不使用联网工作区，可以点开右上角设置图标中的便笺(Scratch Pad)模式  
[**禁用自动更新❗❗❗**](#禁用自动更新)


## 1.下载&安装Postman
### [下载Postman](https://www.postman.com/downloads/)
|最新版本下载|[官方下载页面](https://www.postman.com/downloads/) 下载链接：[Win64](https://dl.pstmn.io/download/latest/win64)  [Win32](https://dl.pstmn.io/download/latest/win32)  [Mac](https://dl.pstmn.io/download/latest/osx)  [Linux](https://dl.pstmn.io/download/latest/linux)  |
|---|---|
|-|**注意** 👇👇👇👇👇 看下面 👇👇👇👇👇 **注意**|
|**历史版本下载**|请把下面链接的"版本号"替换为指定的版本号，例如：8.8.0|
|Windows64位|https://dl.pstmn.io/download/version/版本号/win64|
|Windows32位|https://dl.pstmn.io/download/version/版本号/win32|
|Mac|https://dl.pstmn.io/download/version/版本号/osx|
|Linux|https://dl.pstmn.io/download/version/版本号/linux|

### [安装Postman](https://learning.postman.com/docs/getting-started/installation-and-updates/)


## 2.安装中文包

### 先决条件
1. **安装Postman**
2. **下载对应版本的中文包**

### Windows
1. **下载对应版本的** [**app.zip**](https://gitee.com/hlmd/PostmanCn/releases)
2. **进入**`Postman安装地址/版本/resources`**目录**
   
   > 桌面找到Postman应用程序右键 -> 打开文件所在位置 再进入`app-*.*.*/resources`  
   > 默认安装地址：`C:/Users/用户名/AppData/Local/Postman`  
   > 示例：`C:/Users/用户名/AppData/Local/Postman/app-8.8.0/resources`  
   > ![resources目录地址](https://images.gitee.com/uploads/images/2021/0714/160756_13dcf194_5305579.png "resources目录地址.png")  
3. 复制`app.zip`到`resources`目录  
   > 将`app.zip`解压到当前文件夹 会生成一个`app`目录  
   > 进入`app`目录看到以下图就可以了  
   > ![app目录](https://images.gitee.com/uploads/images/2021/0714/160834_f3317f6c_5305579.png "app目录.png")  
4. 重启Postman就可以了

### 操作GIF
![Postman设置为中文](https://images.gitee.com/uploads/images/2021/0522/004018_9f5050c9_5305579.gif)


### Mac
1. **下载对应版本的** [**app.zip**](https://gitee.com/hlmd/PostmanCn/releases)  
2. **解压** `app.zip`  
3. **进入** `访达/应用程序/Postman.app/Contents/Resources/`
   
   > 进入`访达/应用程序`找到`Postman.app`右键查看包内容，再进入`Contents/Resources`
4. **替换`app`文件夹**
   > 如果目录下没有 `app` 文件夹，那么直接解压 `app.zip` 得到 `app` 文件夹即可  
   > 将`app.zip`解压出来的`app`文件夹复制到`Resources`目录，替换原本的`app`文件夹  
   > 可以先删除或重命名原本的`app`文件夹
5. 重启Postman就可以了

### Linux
1. **下载对应版本的** [**app.zip**](https://gitee.com/hlmd/PostmanCn/releases)
```shell
# 下方为Github地址 将版本号替换为对应版本号，例如：8.8.0
wget https://github.com/hlmd/Postman-cn/releases/download/版本号/app.zip
```
2. **解压&&替换`app`文件夹**
```shell
# Postman安装地址 自行替换
unzip -o -d Postman安装地址/app/resources app.zip
```

## 禁用自动更新❗❗❗
> 这是一项危险操作，将会使你的电脑无法与Postman下载服务器连接，当然这就可以使你的Postman应用程序不再更新  
> 如果想更新请将此解析注释或移除  
> Windows 删除安装目录的update.exe即可  

将此解析加入你电脑的主机文件hosts
```
0.0.0.0         dl.pstmn.io
```
**hosts文件在**  
> **Windows**：`C:/Windows/System32/drivers/etc/hosts`  
> **Linux & Mac**：`/etc/hosts`



