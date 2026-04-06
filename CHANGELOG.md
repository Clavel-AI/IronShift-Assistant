# Changelog

All notable changes to the **IronShift** extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.6.22] — Latest

### ✨ Added
- **Expanded AI Model Roster** — Added Claude Opus 4.6, Claude Sonnet 4.6, GPT-5.4 Pro, Gemini 3 Pro/Flash Preview, and Grok 4 to all tiers
- **Auto Mode** — Intelligent multi-model orchestration (`auto-free` for Standard, `auto-pro` for Pro+) that selects the best model per task automatically
- **IaC File Generator Wizard** — Multi-step guided wizard to generate production-ready Terraform, Ansible, and Kubernetes files, saved directly into `.ironshift/infra/<timestamp>/` in your workspace
- **Terminal Error Auto-Fix ⚡** — `TerminalMonitor` watches all terminal sessions; when a command fails, instantly offers a "Fix with IronShift ⚡" notification. AI analyzes the error and suggests the corrected command to run or copy
- **Credit-Based Usage System** — Transparent token-based billing (1 credit = $0.01). Plans: Free = 30 credits, Pro = 600 credits, Pro Plus = 1,200 credits. Monthly auto-reset
- **Real-Time Credit Tracking** — Live credit deduction after each request with remaining balance shown
- **Workspace Context Manager** — Persistent workspace context stored in VS Code `globalState`, editable via "Manage Workspace Context" command
- **Sensitive Value Store** — SecretStorage-backed store that masks credentials in commands and rehydrates them at execution time
- **Deploy Project Command** — New `IronShift: Deploy Project` command for triggering cloud deployments
- **New Chat Command** — New `IronShift: New Chat` command to start a fresh session instantly
- **Promo Code System** — Backend support for time-limited promotional discount codes (3-month rolling window)
- **Invoice & Billing Emails** — Automatic SendGrid emails for new purchases and subscription renewals

### 🔧 Changed
- **Minimum VS Code version** bumped to `v1.93.0+` (required for shell integration / `onDidEndTerminalShellExecution`)
- **Default model** updated to `gpt-5.2` (was `gpt-5.1`)
- **Plan model tiers** reorganized: Standard / Premium (Pro) / Top-Tier (Pro Plus)
- **OAuth login flow** now passes IDE scheme and name (`ide=vscode&ideName=...`) so the dashboard can redirect back to the correct IDE (supports VS Code, Cursor, Windsurf)
- **Subscription upgrades** now reset billing cycle to today and forgo proration for a cleaner billing experience
- **Output Sanitizer** now strips sensitive values before sending terminal output to the AI

### 🐛 Fixed
- Credit mismatch self-healing: users who upgraded to Pro but still had Free credits are automatically corrected on next request
- Monthly credit reset now correctly handles users who haven't used the app for multiple months
- Subscription plan changes while a promo code is active now permanently expire the promo to prevent billing conflicts

---

## [0.6.x Series] — Feature Expansion

### Summary of v0.6.0 → v0.6.21

- Iterative improvements to the AI chat panel UI (dark mode, streaming, code blocks)
- Rolling model updates as new OpenAI, Anthropic, and Google models launched
- Backend subscription lifecycle management (cancel, resume, upgrade, webhook handling)
- Usage history graphs with per-model token breakdown (7d / 30d / 1y)
- OAuth social login via Google and GitHub
- Rate limiting, Helmet security headers, HTTPS enforcement, NoSQL injection protection
- Session-based auth with MongoDB-backed session store
- Stripe integration: checkout sessions, customer portal, invoice retrieval

---

## [0.1.0] — 2024-12-18

### 🎉 Initial Release

We're excited to introduce **IronShift** — your AI-powered cloud infrastructure copilot for VS Code!

### ✨ Added

- **Natural Language Interface** — Ask questions about your cloud infrastructure in plain English
- **Azure Integration** — Full support for Azure resource management
  - List and manage Resource Groups
  - Virtual Machine operations (list, start, stop, restart)
  - Azure Container Apps management
  - Azure Kubernetes Service (AKS) support
  - Storage Account operations
  - App Service management
- **AWS Integration** — Comprehensive AWS resource support
  - EC2 instance management
  - S3 bucket operations
  - Lambda function management
  - ECS/EKS cluster support
- **Human-in-the-Loop Safety** — All operations require explicit approval before execution
- **Real-Time Streaming** — Instant feedback with streaming responses
- **Integrated Terminal** — Execute commands directly in VS Code's terminal
- **Conversation History** — Persistent chat sessions for context continuity
- **Modern UI** — Beautiful, dark-themed chat interface

### 🔧 Configuration Options

- `ironshift.backendUrl` — Configure custom backend endpoints
- `ironshift.autoApprove` — Optional auto-approval for low-risk operations

---

## Coming Next

### 🚀 Planned Features

- **Scheduled operations** and automation workflows
- **Team collaboration** features
- **Custom tool definitions** for enterprise needs

---

Stay tuned for more updates! Follow our [GitHub repository](https://github.com/Clavel-AI/IronShift-Assistant) and join our [Discord](https://discord.com/invite/ZvYYKcJYE9) for the latest developments.
