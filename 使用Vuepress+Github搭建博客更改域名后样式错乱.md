# 使用Vuepress+Github搭建博客更改域名后样式错乱

## 在搭建github上的网站域名是xxx.github.io/仓库名

## 现在将xxx.github.io/仓库名改为xxx.com后

## 本质原因是路径发生了变化，

## 所以直接把仓库的路径注释掉就可以了

在Config.js中

```javascript
module.exports = {
    title: 'AI教程', // 网站标题
    description: '基础教程，使用技巧', // 网站描述
    theme: 'reco', // 使用 reco 主题，请确保已经安装此主题
   // base: '/仓库名/', //换域名后要注意路径问题
    locales: {
        '/': {
            lang: 'zh-CN', // 设置语言，有助于提升SEO
        },
    },
[【图文教程】ChatGPT4.0如何使用？如何充值，如何升级？有什么使用技巧？需要以什么原则来使用？（附上WildCard邀请码GPT321,享受开通优惠) | AI教程 (ai-sora-chat.com)](https://ai-sora-chat.com/#/)

[一文详解Wildcard虚拟信用卡平台入手指南及解答常见问题，以及如何利用该平台订阅ChatGPT等国外软件的步骤和问题解决方案。 | AI教程 (ai-sora-chat.com)](https://ai-sora-chat.com/#/handbook/Detailed-explanation-of-Wildcard.html)
