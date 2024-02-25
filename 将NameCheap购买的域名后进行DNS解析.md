# 将NameCheap购买的域名后进行DNS解析

## 1.[进入DNS控制台](https://ap.www.namecheap.com/)，会看到你购买的域名，点击manage

![1708826316378](https://chatd.oss-us-east-1.aliyuncs.com/img2/202402250958149.png)

## 2.点击Domain List

![1940f76dcc9087aa2e7ce322636e65c](https://chatd.oss-us-east-1.aliyuncs.com/img2/202402251053058.png)

## 3.点击Advance DNS，开始进行DNS解析配置

1.点击ADD NEW RECORD ,![c6f33759bc2b1c2d6ff789e96c8eb0d](https://chatd.oss-us-east-1.aliyuncs.com/img2/202402251115504.png)

2.Type 为A ,Host 填@  服务器填ip地址

3.Type 为A ,Host 填www  服务器填ip地址

4..Type 为CNAME,Host 填www,  Target填你买的域名地址 比如   GPT321.com

这里的服务器我用的是github的，配置了四个

要将你在Namecheap购买的域名通过A记录指向你的GitHub Pages站点，使用以下由GitHub提供的IP地址：
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
这些IP地址用于配置顶级域名（如example.com），使其指向你的GitHub Pages。设置这些A记录后，DNS变更可能需要一些时间在互联网上传播。

![ff2cb06e07e88e3531c38ab10cb56a0](https://chatd.oss-us-east-1.aliyuncs.com/img2/202402251108659.png)

![ea51853d198b1df1882900ebe0a0c4d](https://chatd.oss-us-east-1.aliyuncs.com/img2/202402251109146.png)

## 结束

配置完后，等待几分钟看一眼

[【图文教程】ChatGPT4.0如何使用？如何充值，如何升级？有什么使用技巧？需要以什么原则来使用？（附上WildCard邀请码GPT321,享受开通优惠) | AI教程 (ai-sora-chat.com)](https://ai-sora-chat.com/#/)

[一文详解Wildcard虚拟信用卡平台入手指南及解答常见问题，以及如何利用该平台订阅ChatGPT等国外软件的步骤和问题解决方案。 | AI教程 (ai-sora-chat.com)](https://ai-sora-chat.com/#/handbook/Detailed-explanation-of-Wildcard.html)
