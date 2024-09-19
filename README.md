# comments

A Server-Less Comment Board, powered by [Valine](https://valine.js.org/) and [LeanCloud](https://www.leancloud.cn/).

## How to USE

- Replace the appKey and appId with your own in index.html
- Deploy index.html on your Gitee

## Generate your appKey and appId

1. 在 [LeanCloud](https://www.leancloud.cn/) 上注册一个账号
2. 借助支付宝实名认证
3. 在 LeanCloud 上 创建一个应用（个人开发版）
4. 进入到你的应用 > 设置 > 应用凭证，生成 appKey 和 appId
5. 你的应用 > 数据存储 > 结构化数据 > 创建 Class，创建一个名为 Counter 的 Class 集合
6. 评论数据存储在：Comment 类里
7. 阅读量数据存储在：Counter 类里
8. 你的应用 > 设置 > 安全中心 > Web 安全域名，添加你的域名，比如：https://yourUserName.gitee.io
9. 你的应用 > 设置 > 安全中心 > 服务开关，只打开 `数据存储`
