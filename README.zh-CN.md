<div align="center">

# Prompt2App

**一句话，生成一个业务系统。**

开源的 AI 业务应用生成平台：用一句自然语言，生成可直接运行的 ERP、CRM、OA、进销存、审批流等业务系统。
不想写代码？零代码直接用。想深度定制？低代码随时接管。

[官网](https://prompt2app.cn) · [English](./README.md) · [文档](https://prompt2app.cn/docs) · [在线体验](https://prompt2app.app)

![License](https://img.shields.io/badge/license-Apache--2.0-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)
![Status](https://img.shields.io/badge/status-早期开发中-orange)

<!-- 替换为 30 秒演示 GIF：输入一句话 → 出现一个可用的 CRM -->
<img src="docs/assets/demo.gif" alt="Prompt2App 演示" width="800" />

</div>

---

## ✨ Prompt2App 是什么？

开发一个企业内部业务系统，依然又慢又贵。传统低代码平台快了一些，但仍然要拖拽、配置好几天。

Prompt2App 让这一步直接消失。你只需要说：

> “帮我做一个进销存系统，包含采购单、库存预警，金额超过 5 万的订单需要两级审批。”

Prompt2App 会自动生成完整系统：数据模型、页面、表单、权限、流程和报表。生成的是一个真实可运行的应用，可以马上使用，也可以继续对话迭代。

## 🚀 核心特性

- **一句话生成应用**：描述需求，得到完整可运行的业务系统。
- **零代码**：业务人员通过对话即可创建和修改应用。
- **低代码**：开发者可打开可视化编辑器或生成的源码，自由定制。
- **开箱即用的业务能力**：数据建模、增删改查、角色权限、审批流、仪表盘与报表。
- **对话式迭代**：“加一个客户等级字段”“成交后自动发邮件”，系统即时更新。
- **模型无关**：支持 Claude、GPT、DeepSeek、通义千问及本地模型，LLM 层可插拔。
- **私有部署、完全开源**：数据留在自己的服务器上，代码随时导出，不被平台绑定。

## 🧩 可以生成什么？

| 类别 | 示例 |
|---|---|
| ERP | 采购、销售、库存、财务 |
| CRM | 线索、客户、商机漏斗、跟进记录 |
| OA | 审批、请假、报销、公告 |
| 运营管理 | 资产管理、工单、排班 |
| 更多 | 只要能描述清楚，Prompt2App 就能先帮你搭出来 |

## ⚡ 快速开始

```bash
# 克隆项目
git clone https://github.com/prompt2app/prompt2app.git
cd prompt2app

# 配置大模型
cp .env.example .env

# 启动
docker compose up -d
```

打开 `http://localhost:3000`，输入你的第一句话。

> ⚠️ 项目处于早期开发阶段，命令和接口可能会调整。

## 🏗️ 工作原理

```
一句话需求 → 需求分析 → 数据模型 → 页面与流程 → 可运行应用
            (LLM Agent)  (模型生成)  (页面/流程生成)  (部署/导出)
                 ↑                                      │
                 └──────────── 对话持续优化 ─────────────┘
```

## 🗺️ 路线图

- [ ] 一句话生成数据模型与增删改查页面
- [ ] 角色权限体系
- [ ] 可视化流程 / 审批引擎
- [ ] 仪表盘与报表
- [ ] 可视化低代码编辑器
- [ ] 源码导出
- [ ] 应用模板市场
- [ ] 插件与 API 集成

## 🤝 参与贡献

欢迎任何形式的贡献：代码、文档、应用模板、Bug 反馈和功能建议。
详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## ⭐ 支持项目

如果你觉得 Prompt2App 有用，请点一个 Star，让更多人看到它。

## 📄 开源协议

[Apache License 2.0](./LICENSE)
