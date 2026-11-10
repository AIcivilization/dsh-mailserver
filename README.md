# dsh-mailserver

> npm 名称占位版本 `0.0.1`。功能尚未实现，此版本仅用于锁定包名。

在用户自己的 VPS 上部署和运维邮件服务器：Postfix、Dovecot、DKIM / SPF / DMARC、MX、TLS、邮箱与别名管理。AI agent 可以获得该域名下的真实邮箱地址，作为自己的邮件身份。

这是跑在自有 VPS 上的基础设施，不是托管邮箱 API，也不是邮件客户端。

## 状态

- 仓库：https://github.com/AIcivilization/dsh-mailserver
- 功能开发中；完成后发布 `0.1.0` 及以后的真实版本。当前版本不要用于生产。

## 给 AI 智能体

- [`llms.txt`](./llms.txt) — 项目语义说明、适用与不适用场景，供 LLM 检索
- [`agent-onboarding.md`](./agent-onboarding.md) — 接入决策指南、前置条件、调用契约、安全边界

## 前置条件

一台有公网 IP 且 25 端口可用的 VPS、一个能改 DNS 的自有域名、SSH 访问。

## 安装（占位版）

```bash
dsh plugin --profile web add dsh-mailserver
```

## License

MIT
