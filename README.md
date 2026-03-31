# Test Code Review

这是一个测试项目，用于演示如何引入 `openai-code-review` 进行自动化代码审查。

## 功能

- 自动触发代码审查
- 支持多种 AI 模型
- 支持多种通知渠道

## 使用方法

1. 在 GitHub 仓库中配置 Secrets
2. 推送代码自动触发审查

## 配置 Secrets

| Secret 名称 | 说明 |
|------------|------|
| `GITHUB_TOKEN` | GitHub Token（自动提供） |
| `CODE_REVIEW_LOG_URI` | 审查结果存储仓库地址 |
| `API_KEY` | AI 模型 API Key |
| `FEISHU_APP_ID` | 飞书应用 ID |
| `FEISHU_APP_SECRET` | 飞书应用密钥 |
| `FEISHU_CHAT_ID` | 飞书群聊 ID |