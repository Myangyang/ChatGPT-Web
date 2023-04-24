<div align="center">
<img src="./docs/images/icon.svg" alt="预览"/>

<h1 align="center">ChatGPT Web</h1>

一键免费部署你的私人 ChatGPT 网页应用。

[演示 Demo](https://chat.quanguoxinxi.cn//) /  [部署同款](https://ext.dcloud.net.cn/plugin?id=11680) /  [打赏开发者](https://mp-2f0d48ab-d929-4cc0-95a3-4a6bd2716330.cdn.bspapp.com/cloudstorage/b1e4674d-fe06-43c6-b94b-cf0cd11a7890.jpg) 

![主界面](./docs/images/cover.png)


## 主要功能

- 精心设计的 UI，响应式设计，支持深色模式
- 极快的首屏加载速度（~100kb）
- 自动压缩上下文聊天记录，在节省 Token 的同时支持超长对话
- 一键导出聊天记录，完整的 Markdown 支持

## 开始使用

1. 准备好你的 **OpenAI API Key**
2. （可选）域名 DNS 在某些区域被污染了，绑定自定义域名即可直连。


## 配置页面访问密码

> 配置密码后，用户需要在设置页手动填写访问码才可以正常聊天，否则会通过消息提示未授权状态。

> **警告**：请务必将密码的位数设置得足够长，最好 7 位以上，否则**会被爆破**


## 环境变量

> 本项目大多数配置项都通过环境变量来设置。

### `OPENAI_API_KEY` （必填项）

OpanAI 密钥，你在 openai 账户页面申请的 api key。

### `CODE` （可选）

访问密码，可选，可以使用逗号隔开多个密码。

**警告**：如果不填写此项，则任何人都可以直接使用你部署后的网站，可能会导致你的 token 被急速消耗完毕，建议填写此选项。

