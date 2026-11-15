# Linker 问题反馈

这里收集 Linker 的故障、兼容性问题和功能建议，也用于查看处理进度。

- [提交问题](https://github.com/Linker-DEV-Team/linker-feedback/issues/new/choose)
- [查找已有问题](https://github.com/Linker-DEV-Team/linker-feedback/issues)
- [官网与下载](https://baigave.cn/support.html) · [发行版本](https://github.com/Linker-DEV-Team/linker-releases/releases)

## 怎么反馈

先搜索是否已有相同问题。已有的请在原问题下补充版本、复现步骤，或用 👍 表示也遇到了。新问题请选择「故障反馈」「兼容性反馈」或「功能建议」，按表单填写。

提交需要登录 GitHub。无法使用 GitHub，或者材料涉及隐私时，可以发邮件到 **support@baigave.cn**；邮件不会自动进入这里的处理列表。

Blender 顶栏的 **Linker Diagnostics / Linker 诊断** 可以导出诊断 ZIP。提交前请查看内容：已知密钥和用户目录会被过滤，但日志仍可能含有聊天、用户名、服务器地址或素材名称。只上传确认可以公开的材料；私人工程、存档、授权码、账号、订单和未经允许分享的素材请勿放在公开 Issue 中。私密材料请通过邮件发送，并注明 Issue 编号。

## 怎么处理

开发机和服务可用时，自动处理任务每两小时检查一次反馈。回复可能由 AI 辅助生成。信息不全会说明需要补充什么；信息完整且能够验证的问题会尝试复现、修复并测试。复杂兼容问题和新功能可能需要进一步评审，每次检查不等于每个问题都会立即修好。

| 标签 | 含义 |
| --- | --- |
| `status:triage` | 等待检查、查重和分类 |
| `status:needs-info` | 需要补充版本、复现步骤或材料 |
| `status:ready` | 已具备处理条件 |
| `status:in-progress` | 正在复现、修复或验证 |
| `status:needs-review` | 修复已提交，等待评审 |
| `status:awaiting-release` | 修复已合入，等待可下载版本 |
| `status:blocked` | 缺少运行环境、参考源码或其他必要条件 |
| `status:released` | 修复已发布，会说明版本和下载地址 |

测试通过与正式发布会分别说明。发布后请按原步骤复测；仍有问题可以继续在原 Issue 下补充，维护者会重新打开它。

## English

Use the issue forms to report bugs, compatibility problems, or feature requests. You may write in English. Include exact versions, reproduction steps, expected and actual behavior, and public-safe evidence. Search existing issues before opening a new one.

Issues and attachments are public. Send private material to **support@baigave.cn** with the issue number. Automated checks run every two hours when the development machine and services are available; a check is not a promise of an immediate fix. We distinguish tested fixes from released builds.
