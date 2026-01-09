<p align="center">
  <img src="assets/logo.png" alt="IronShift Logo" width="150" height="150">
</p>

<h1 align="center">☁️ IronShift - AI-Powered Cloud Infrastructure Copilot</h1>

<p align="center">
  <strong>Manage Azure & AWS through natural conversation—right inside VS Code</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/visual-studio-marketplace/v/IronShift.ironshift?style=for-the-badge&logo=visual-studio-code&logoColor=white&label=VS%20Code&color=007ACC" alt="VS Code Marketplace">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/visual-studio-marketplace/d/IronShift.ironshift?style=for-the-badge&logo=visual-studio-code&logoColor=white&label=Downloads&color=4CAF50" alt="Downloads">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/visual-studio-marketplace/r/IronShift.ironshift?style=for-the-badge&logo=visual-studio-code&logoColor=white&label=Rating&color=FFC107" alt="Rating">
  </a>
</p>

<p align="center">
  <a href="#-what-is-ironshift">What is IronShift</a> •
  <a href="#-key-features">Features</a> •
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-supported-clouds">Clouds</a> •
  <a href="#-support">Support</a>
</p>

---

## 🚀 What is IronShift?

**IronShift** is your AI-powered cloud infrastructure copilot that lives right inside VS Code. Stop context-switching between your IDE, cloud consoles, and documentation.

> Just ask IronShift what you need, and it will manage, troubleshoot, and automate your cloud infrastructure—with your approval.

<p align="center">
  <img src="assets/demo.png" alt="IronShift Demo" width="800">
</p>

---

## ✨ Key Features

### 🗣️ Natural Language Interface
Ask questions in plain English. No need to memorize CLI commands or navigate complex cloud consoles.

```
"List all my Azure VMs in the production resource group"
"What's the status of my Kubernetes pods?"
"Show me the logs for my container app"
"Start the VM named web-server-01"
```

<p align="center">
  <img src="assets/feature-chat.png" alt="Natural Language Chat" width="700">
</p>

---

### ☁️ Multi-Cloud Support
Seamlessly manage resources across multiple cloud providers from a single interface.

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Amazon%20AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Google%20Cloud-Coming%20Soon-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="GCP">
</p>

---

### �️ Human-in-the-Loop Safety
Every action is reviewed before execution. **You stay in control.**

<p align="center">
  <img src="assets/feature-approval.png" alt="Action Approval" width="700">
</p>

IronShift shows you:
- ✅ The exact tool/command to be executed
- ✅ All parameters and arguments
- ✅ Risk assessment for each operation

**Approve, modify, or reject any action before it runs.**

---

### 🤖 Multiple AI Models
Choose from the best AI models for your needs:

| Model | Provider | Best For |
|-------|----------|----------|
| **GPT-4.1** | Azure OpenAI | Complex reasoning & troubleshooting |
| **GPT-4o** | Azure OpenAI | Fast, high-performance responses |
| **Claude Sonnet 4.5** | Anthropic | Detailed analysis & explanations |
| **Claude Sonnet 4** | Anthropic | Balanced performance |

---

### ⚡ Real-Time Streaming
Get instant feedback with real-time streaming responses. Watch as IronShift analyzes your request and provides step-by-step results.

---

### 🖥️ Integrated Terminal Execution
Execute cloud commands directly in VS Code's integrated terminal. See command outputs in real-time without leaving your editor.

---

### � Conversation History
Your chat sessions are preserved. Continue where you left off, or review past troubleshooting sessions for reference.

---

## 📦 Quick Start

### Installation

1. Open **Visual Studio Code**
2. Go to **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **"IronShift"**
4. Click **Install**

Or install directly:
```
ext install IronShift.ironshift
```

### Prerequisites

- **VS Code** v1.85.0 or later
- **Azure CLI** (for Azure operations) - [Install Guide](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
- **AWS CLI** (for AWS operations) - [Install Guide](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

### Getting Started

1. Click the **IronShift** icon in the Activity Bar
2. Authenticate with your cloud provider when prompted
3. Start asking questions in natural language!

---

## ☁️ Supported Clouds & Operations

### Microsoft Azure
| Category | Operations |
|----------|------------|
| **Resource Groups** | List, Create, Delete |
| **Virtual Machines** | List, Start, Stop, Restart, Get Status |
| **Container Apps** | List, Manage, View Logs |
| **Kubernetes (AKS)** | Cluster Management, Pod Status |
| **Storage Accounts** | List, Manage |
| **App Services** | Deploy, Configure, Monitor |

### Amazon AWS
| Category | Operations |
|----------|------------|
| **EC2 Instances** | List, Start, Stop, Terminate |
| **S3 Buckets** | List, Create, Manage Objects |
| **Lambda Functions** | List, Invoke, View Logs |
| **ECS/EKS Clusters** | Cluster & Service Management |
| **IAM Resources** | Users, Roles, Policies |

---

## ⚙️ Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| `ironshift.backendUrl` | IronShift Cloud | Backend service URL (enterprise deployments) |
| `ironshift.autoApprove` | `false` | Auto-approve low-risk read operations |
| `ironshift.defaultModel` | `gpt-4.1` | Default AI model for responses |

---

## 🔒 Security & Privacy

- 🔐 **Credentials stay local** — Uses your existing CLI authentication
- 👁️ **Human-in-the-loop** — All write operations require explicit approval
- 📋 **Audit trail** — Every action logged in conversation history
- 🏢 **Enterprise ready** — Self-host your own backend for complete control

---

## 🛣️ Roadmap

- [ ] **Google Cloud Platform (GCP)** support
- [ ] **Terraform** integration for IaC management
- [ ] **Cost analysis** and optimization suggestions
- [ ] **Scheduled operations** and automation workflows
- [ ] **Team collaboration** features
- [ ] **Custom tool definitions** for enterprise needs

---

## 💬 Support, Feedback & Community

- 🐛 **Bug Reports:** [GitHub Issues](https://github.com/ironshift/ironshift-vscode/issues)
- 💡 **Feature Requests:** [GitHub Discussions](https://github.com/ironshift/ironshift-vscode/discussions)
- 📧 **Email:** support@ironshift.dev
- 🌐 **Website:** [https://ironshift.dev](https://ironshift.dev)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ by the <strong>IronShift Team</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/🚀%20Install%20Now-VS%20Code%20Marketplace-007ACC?style=for-the-badge" alt="Install Now">
  </a>
</p>

<p align="center">
  <strong>Happy Cloud Managing! ☁️</strong>
</p>
