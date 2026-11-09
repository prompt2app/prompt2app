<div align="center">

# Prompt2App

**One sentence. One business system.**

An open-source AI platform for generating business applications: describe what you need in plain language and get a ready-to-run ERP, CRM, OA, inventory, approval-workflow system and more.
Don't want to write code? Use it with zero code. Need deep customization? Take over with low code at any time.

[Website](https://prompt2app.cn) · [中文](./README.zh-CN.md) · [Docs](https://prompt2app.cn/docs) · [Live Demo](https://prompt2app.app)

![License](https://img.shields.io/badge/license-Apache--2.0-blue)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen)
![Status](https://img.shields.io/badge/status-early%20development-orange)

<!-- Replace with a 30-second demo GIF: type one sentence → a working CRM appears -->
<img src="docs/assets/demo.gif" alt="Prompt2App demo" width="800" />

</div>

---

## ✨ What is Prompt2App?

Building internal business systems is still slow and expensive. Traditional low-code platforms speed things up, but you still spend days dragging, dropping and configuring.

Prompt2App removes that step entirely. Just say:

> "Build me an inventory management system with purchase orders and low-stock alerts. Orders over 50,000 need two levels of approval."

Prompt2App generates the complete system: data models, pages, forms, permissions, workflows and reports. What you get is a real, running application — use it right away, or keep refining it through conversation.

## 🚀 Key Features

- **One sentence to an app**: describe your requirements and get a complete, runnable business system.
- **Zero code**: business users create and modify apps just by chatting.
- **Low code**: developers can open the visual editor or the generated source code and customize freely.
- **Business capabilities out of the box**: data modeling, CRUD, role-based permissions, approval workflows, dashboards and reports.
- **Conversational iteration**: "Add a customer tier field", "Send an email automatically when a deal closes" — the system updates instantly.
- **Model-agnostic**: supports Claude, GPT, DeepSeek, Qwen and local models through a pluggable LLM layer.
- **Self-hosted and fully open source**: your data stays on your own servers, your code can be exported anytime — no platform lock-in.

## 🧩 What can it build?

| Category | Examples |
|---|---|
| ERP | Purchasing, sales, inventory, finance |
| CRM | Leads, customers, sales pipeline, follow-ups |
| OA | Approvals, leave requests, expense claims, announcements |
| Operations | Asset management, work orders, shift scheduling |
| More | If you can describe it clearly, Prompt2App can build the first version for you |

## ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/prompt2app/prompt2app.git
cd prompt2app

# Configure your LLM
cp .env.example .env

# Start
docker compose up -d
```

Open `http://localhost:3000` and type your first sentence.

> ⚠️ The project is in early development. Commands and APIs may change.

## 🏗️ How It Works

```
Prompt → Requirement analysis → Data model → Pages & workflows → Running app
            (LLM Agent)         (model gen)   (page/flow gen)    (deploy/export)
                 ↑                                                    │
                 └──────────── Continuous refinement via chat ────────┘
```

## 🗺️ Roadmap

- [ ] Generate data models and CRUD pages from one sentence
- [ ] Role-based permission system
- [ ] Visual workflow / approval engine
- [ ] Dashboards and reports
- [ ] Visual low-code editor
- [ ] Source code export
- [ ] App template marketplace
- [ ] Plugins and API integrations

## 🤝 Contributing

All kinds of contributions are welcome: code, docs, app templates, bug reports and feature requests.
See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## ⭐ Support the Project

If you find Prompt2App useful, please give it a Star so more people can discover it.

## 📄 License

[Apache License 2.0](./LICENSE)
