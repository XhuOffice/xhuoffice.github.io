---
layout: post
title: 如何科学上网
author: Session Hu
keywords: [XhuOffice, v2ray, 科学上网, v2rayN, Windows]
permalink: /Notes/2023-05-27-How-2-use-Internet/
---

## 注意事项

### **中国大陆用户请立即离开本页面！以此造成的法律后果请自行承担！**  

## 准备工作

- 一台能连接 Internet 的 Windows 7 及以上系统且能正常使用的计算机

- 一个会进行思考与操作计算机的生物

## 步骤

1. 打开 <https://github.com/2dust/v2rayN/releases> 下载最新版本的`v2rayN`，不用管是不是`Pre-release`，不过一定要下载**带Core**的版本。[这](https://github.com/2dust/v2rayN/releases/download/6.25/v2rayN-With-Core.zip "v2rayN v6.24")是我<abbr title="2023/5/27 13:45:01">现在</abbr>使用的版本的下载直链。

    ![下载](/images/Notes/20230527/00000001-1.png)

2. 将下载的压缩包解压缩到一个合适的位置，并创建好快捷方式。

3. 右键`v2rayN.exe`点击`属性(&R)`，在兼容性选项卡中将`以管理员身份运行此程序`打上勾，然后点击确定以保存设置。

    ![管理员身份运行](/images/Notes/20230527/00000001-2.png)

4. 运行`v2rayN.exe`或打开其快捷方式。

5. 复制以下文字，并在v2rayN主界面中按下`Ctrl+C`

    ```text
    https://ghproxy.com/https://raw.githubusercontent.com/aiboboxx/v2rayfree/main/v2
    https://ghproxy.com/https://raw.githubusercontent.com/freefq/free/master/v2
    https://ghproxy.com/https://raw.githubusercontent.com/ssrsub/ssr/master/V2Ray
    https://ghproxy.com/https://raw.githubusercontent.com/SessionHu/SessionHu/main/V2RaySubInfo.txt
    ```

6. 点击`订阅分组`，选择`更新全部订阅(通过代理)`（若节点不可用则不通过代理）。

    ![更新订阅](/images/Notes/20230527/00000001-3.png)

7. 稍作等待，在更新订阅完成后，在节点列表内右键，选择`移除重复的服务器`。

    ![去重](/images/Notes/20230527/00000001-4.png)

8. 然后在列表内选择一个喜欢的按下`Enter`连接，若节点不可用再找一个。

9. 接下来是个性化配置，推荐开机自启且启用统计
