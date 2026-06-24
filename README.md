# 🤖 AI HOT 每日晨报

> 由 [AI HOT](https://aihot.virxact.com) 数据驱动的 AI 行业每日精选仪表盘，每日 08:00（北京时间）自动更新。

**🔗 在线访问：https://haciii-agent.github.io/ai-hot-daily/**

---

## 关于 AI HOT

[AI HOT](https://aihot.virxact.com) 中文 AI 资讯聚合平台，每日精选全球 AI 领域最重要的动态，涵盖大模型发布、产品更新、学术论文、行业趋势等方向。

---

## 晨报内容

每日晨报按 **五个固定版块** 组织：

| 版块 | 说明 |
|---|---|
| 🧠 模型发布/更新 | 大模型新版本、开源权重、技术报告 |
| 🚀 产品发布/更新 | AI 产品上线、功能迭代、工具发布 |
| 📡 行业动态 | 投资融资、政策监管、公司战略 |
| 📄 论文研究 | 重要学术论文、技术突破、Benchmark |
| 💡 技巧与观点 | 实战技巧、行业洞察、深度观点 |

每期精选 20-30 条资讯，全局连续编号，附带来源标注与原文跳转。

---

## 技术实现

- **数据源**：AI HOT 公开 API
- **前端**：纯 HTML/CSS/JS 单文件，暗色主题，响应式布局，零外部依赖
- **托管**：[GitHub Pages](https://haciii-agent.github.io/ai-hot-daily/)（`main` 分支 `/` 根目录）
- **自动化**：WorkBuddy 每日定时任务 → 拉取数据 → 生成 HTML → 推送 GitHub → 钉钉通知

### 文件结构

```
ai-hot-daily/
├── index.html            # 始终是最新一期（Pages 首页）
├── daily/                # 历史归档
│   ├── 2026-06-24.html
│   └── ...
└── README.md
```

`index.html` 每天被覆盖为最新内容；历史日报永久保存在 `daily/` 目录下，可通过 `daily/YYYY-MM-DD.html` 访问。

---

## 更新频率

每日 **08:00（北京时间）** 自动更新，节假日无休。若当日 AI HOT 尚未生成数据，自动回退到最近一期可用日报。

---

## 贡献与反馈

本项目为自动生成工具，不接收代码 PR。

- 资讯内容问题请访问 [AI HOT](https://aihot.virxact.com) 反馈
- 仪表盘功能建议可通过钉钉联系维护者

---

*🤖 由 WorkBuddy AI 自动生成与维护 · 数据来源 [AI HOT](https://aihot.virxact.com)*
