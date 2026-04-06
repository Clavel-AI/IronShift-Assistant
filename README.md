<h1 align="center">IronShift — AI-Powered Cloud Infrastructure Copilot</h1>

<p align="center">
  <strong>Works in VS Code, Cursor, Windsurf, and any VS Code-compatible IDE</strong>
</p>

<p align="center">
  <strong>Manage any cloud or DevOps tool through natural conversation—right inside your IDE</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Version-0.6.22-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Installs-50+-4CAF50?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Installs">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Rating-5%2F5-FFC107?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Rating">
  </a>
  <a href="https://x.com/ironshift21128">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://discord.com/invite/ZvYYKcJYE9">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://www.linkedin.com/company/clavelai/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.reddit.com/r/Ironshiftofficial/">
    <img src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white" alt="Reddit">
  </a>
</p>

<p align="center">
  <a href="#what-is-ironshift">What is IronShift</a> •
  <a href="#supported-ides">Supported IDEs</a> •
  <a href="#key-features">Features</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#supported-tools--operations">Tools</a> •
  <a href="#plans--pricing">Plans</a> •
  <a href="#support-feedback--community">Support</a>
</p>

---

## **What is IronShift?**

**IronShift** is the AI-powered cloud infrastructure copilot that helps SREs and cloud developers manage, troubleshoot, and automate cloud resources—all within your favourite IDE. Whether you use **VS Code**, **Cursor**, **Windsurf**, or any other VS Code-compatible editor, IronShift works seamlessly across all of them. Stop context-switching between your IDE, cloud consoles, and documentation.

> Just ask IronShift what you need, and it will execute cloud operations, analyze infrastructure, and provide intelligent recommendations—with your approval. Works natively in VS Code, Cursor, Windsurf, and more.

### **With IronShift, you get:**

✅ **Natural Language Interface** — Ask questions in plain English, no CLI memorization needed  
✅ **Universal Tool Support** — Azure, AWS, GCP, Docker, Terraform, Kubernetes, Ansible, and more  
✅ **Human-in-the-Loop Safety** — Every action reviewed before execution, you stay in control  
✅ **11 AI Models** — Choose from GPT-5.2, Claude Sonnet 4.6, Gemini 3, Grok 4, and more  
✅ **Auto Mode** — Intelligent multi-model orchestration that picks the best model per task  
✅ **Real-Time Streaming** — Watch as IronShift analyzes and executes step-by-step  
✅ **Vision Support** — Attach screenshots for context-aware troubleshooting  
✅ **OS-Aware Commands** — Automatically detects your OS and generates the right CLI syntax  
✅ **Terminal Error Auto-Fix** — "Fix with IronShift ⚡" appears instantly when a terminal command fails  
✅ **IaC File Generator** — Guided wizard to generate Terraform, Ansible, and Kubernetes files  

Designed for **SREs, DevOps engineers, and cloud developers**, IronShift helps you operate cloud infrastructure smarter, faster, and more securely—no matter which IDE you use. 🚀

<p align="center">
  <img src="https://raw.githubusercontent.com/Clavel-AI/IronShift-Assistant/main/assets/Video%20Project%20(1).gif" alt="IronShift Demo" width="800">
</p>

---

## **Supported IDEs**

IronShift is built on the VS Code Extension API and works natively across all VS Code-compatible editors:

| IDE | URI Scheme | Status |
|-----|------------|--------|
| **Visual Studio Code** | `vscode://` | ✅ Fully Supported |
| **Cursor** | `cursor://` | ✅ Fully Supported |
| **Windsurf** | `windsurf://` | ✅ Fully Supported |
| **Any VS Code-compatible IDE** | Auto-detected | ✅ Supported |

The extension automatically detects which IDE you're running in using `vscode.env.uriScheme` and `vscode.env.appName`. The OAuth login flow passes your IDE identity to the dashboard so the auth callback is redirected back to the **correct IDE** — no manual configuration needed.

> **How it works:** When you log in, IronShift sends your IDE's URI scheme (e.g. `cursor`) to the dashboard. After authentication via Google or GitHub, the dashboard redirects to `cursor://ironshift/auth-callback?token=...` — ensuring the token lands in the right application automatically.

---

## **Key Features**

### **Manage Cloud Resources with Natural Language**

Ask questions in plain English and let IronShift handle the complex CLI commands and API calls.

✅ **No CLI memorization** — Just describe what you want  
✅ **Context-aware responses** — IronShift understands your infrastructure  
✅ **Instant results** — Get answers in seconds, not minutes  

```
"List all my Azure VMs in the production resource group"
"What's the status of my Kubernetes pods?"
"Show me the logs for my container app"
"Start the VM named web-server-01"
"Create a storage account in West US region"
```

---

### **Universal Tool Support — Any CLI, One Interface**

Seamlessly manage resources across cloud providers and DevOps tools from a single, unified interface.

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure">
  <img src="https://img.shields.io/badge/Amazon%20AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="GCP">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
</p>

✅ **Ask anything** — Query, manage, and automate any resource  
✅ **Natural language** — No need to memorize service names or syntax  
✅ **Works with any CLI** — If it runs in the terminal, IronShift can help  

---

### **Terminal Error Auto-Fix ⚡**

When a terminal command fails, IronShift instantly detects it and offers a one-click fix—no copy-pasting errors needed.

✅ **Automatic detection** — Monitors all your terminal sessions for failed commands  
✅ **Instant offer** — "Fix with IronShift ⚡" notification appears the moment a command fails  
✅ **AI-powered fix** — Analyzes the failed command and its error output to produce the corrected command  
✅ **Run or Copy** — Execute the fix directly in the same terminal, or copy it to clipboard  
✅ **Safe** — You always review the suggested fix before it runs  

> Requires VS Code `v1.93.0+` for shell integration support.

---

### **IaC File Generator — Infrastructure Wizard**

Generate production-ready infrastructure files in seconds through a guided multi-step wizard.

✅ **Terraform** — Generate `.tf` files for AWS, Azure, or GCP resources  
✅ **Ansible** — Generate playbooks for server configuration and deployment  
✅ **Kubernetes** — Generate Deployment, Service, and HPA manifests  
✅ **Saved to workspace** — Files are placed in `.ironshift/infra/<timestamp>/` for easy access  
✅ **One-click execution** — Suggested CLI commands to apply the generated files immediately  

---

### **Cost Optimization on AWS**

Analyze costs, identify savings opportunities, and optimize your AWS spending—all through natural conversation.

<p align="center">
  <img src="https://raw.githubusercontent.com/Clavel-AI/IronShift-Assistant/main/assets/Demo%203.gif" alt="AWS Cost Optimization Demo" width="800">
</p>

✅ **Query AWS costs** — Get instant insights on your cloud spending  
✅ **Identify savings** — Find underutilized resources and optimization opportunities  
✅ **Natural workflow** — Ask questions like "What are my top spending services?"  

---

### **Observability & Monitoring on Azure**

Analyze logs, monitor application health, and get deep insights with Application Insights—right from your IDE.

<p align="center">
  <img src="https://raw.githubusercontent.com/Clavel-AI/IronShift-Assistant/main/assets/Demo%204.gif" alt="Azure Observability Demo" width="800">
</p>

✅ **Log analysis** — Query and analyze Azure Monitor logs effortlessly  
✅ **Application Insights** — Dive deep into app performance and diagnostics  
✅ **Observability made easy** — Understand your infrastructure health at a glance  

---

### **Three Powerful Operation Modes**

Choose the right mode for your task:

| Mode | Description | Best For |
|------|-------------|----------|
| **Chat** | Quick Q&A and information retrieval | Getting quick answers about your infrastructure |
| **Plan** | Generate step-by-step plans before execution | Complex operations requiring review |
| **Agent** | Autonomous execution with approval checkpoints | Hands-free automation with safety controls |

---

### **Human-in-the-Loop Safety — You Stay in Control**

Every action is reviewed before execution. IronShift never runs a command without your explicit approval.

<p align="center">
  <img src="https://raw.githubusercontent.com/Clavel-AI/IronShift-Assistant/main/assets/feature-approval.png" alt="Action Approval" width="800">
</p>

✅ **See the exact command** — Full transparency on what will run  
✅ **Review all parameters** — Understand every argument before execution  
✅ **Risk assessment** — Know the impact of each operation  
✅ **Approve, modify, or reject** — Complete control at every step  

---

### **11 Industry-Leading AI Models + Auto Mode**

Choose from 11 AI models across 4 providers, or use **Auto Mode** to let IronShift pick the best model automatically for each task.

#### Standard Models (Starter — Free)

| Model | Provider | Best For |
|-------|----------|----------|
| **GPT-5.2** | OpenAI | Complex reasoning & troubleshooting |
| **GPT-5.2 Pro** | OpenAI | Fast, efficient responses |
| **Gemini 2.5 Pro** | Google | Advanced reasoning & multimodal tasks |
| **Gemini 2.5 Flash** | Google | Speed-optimized responses |
| **Grok 4** | xAI | Real-time knowledge & creative solutions |
| **Auto Mode (Free)** | Multi-Model | Automatic model selection for standard tasks |

#### Premium Models (Pro — $10/mo)

| Model | Provider | Best For |
|-------|----------|----------|
| **GPT-5.4** | OpenAI | Advanced next-gen reasoning |
| **Claude Sonnet 4.6** | Anthropic | Detailed analysis & explanations |
| **Claude Sonnet 4.5** | Anthropic | Balanced performance |
| **Gemini 3 Pro Preview** | Google | Google's most capable model |
| **Gemini 3 Flash Preview** | Google | Google's fastest next-gen model |
| **Auto Mode (Pro)** | Multi-Model | Automatic model selection using premium models |

#### Top-Tier Models (Pro Plus — $20/mo)

| Model | Provider | Best For |
|-------|----------|----------|
| **GPT-5.4 Pro** | OpenAI | Most capable OpenAI model |
| **Claude Opus 4.6** | Anthropic | Deepest analysis & problem-solving |
| **Claude Opus 4.5** | Anthropic | Exceptional long-form reasoning |

*No API key management needed—IronShift handles model access based on your plan.*

---

### **Image Attachments & Vision**

Attach screenshots or diagrams for context-aware assistance. Perfect for troubleshooting errors or sharing architecture diagrams.

✅ **Paste** images directly from clipboard (`Ctrl+V` / `Cmd+V`)  
✅ **Drag & drop** files into the chat  
✅ **Browse** to select multiple images  
✅ **Supports** PNG, JPG, GIF, WebP (up to 10MB)  

*Great for sharing error screenshots, architecture diagrams, or console outputs.*

---

### **Smart Chat Management**

Keep your conversations organized and pick up right where you left off.

✅ **Persistent History** — All chats saved locally (privacy-first)  
✅ **Multiple Sessions** — Switch between different conversations  
✅ **Edit & Retry** — Modify previous messages and regenerate responses  
✅ **Auto-cleanup** — Empty chats are automatically removed  
✅ **New Chat** — Start a fresh session instantly from the Command Palette  

---

### **Real-Time Streaming & Batch Execution**

Get instant feedback with real-time streaming responses. Execute multiple commands in sequence with live progress tracking.

✅ **Watch AI think** — See step-by-step analysis in real-time  
✅ **Batch operations** — Queue multiple commands with progress tracking  
✅ **Live output** — See command results as they execute  
✅ **Integrated terminal** — Execute directly in VS Code's terminal  

---

## **Quick Start**

### **Installation**

**In VS Code, Cursor, or Windsurf:**
1. Open your IDE
2. Go to **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **"IronShift"**
4. Click **Install**

Or install directly from any compatible IDE's terminal:
```
ext install IronShift.ironshift
```

### **Prerequisites**

| Requirement | Version | Purpose |
|-------------|---------|----------|
| **VS Code / Cursor / Windsurf** | v1.93.0+ equivalent | IDE (shell integration for Terminal Auto-Fix) |
| **Any CLI** | Latest | Cloud/DevOps operations |

IronShift works with any CLI tool you have installed. Common examples:
- **Azure CLI** (`az`) — Azure operations
- **AWS CLI** (`aws`) — AWS operations  
- **gcloud CLI** — GCP operations
- **Docker** — Container management
- **kubectl** — Kubernetes operations
- **Terraform** — Infrastructure as Code
- **Ansible** — Configuration management

### **Getting Started**

1. Click the **IronShift** icon in the Activity Bar (sidebar) — visible in VS Code, Cursor, Windsurf, and compatible IDEs
2. **Sign up or log in** via the IronShift dashboard (opens in your browser)
3. The OAuth callback is automatically routed back to your IDE — no manual token copying needed
4. Start asking questions in natural language!

> **Tip:** You can also log in by running the command **"IronShift: Login to IronShift"** from the Command Palette, or paste a token manually with **"IronShift: Login with Token"**.

---

## **Authentication**

IronShift uses a secure OAuth-based login flow that works across all supported IDEs:

1. Click **Login** in the chat panel or run **"IronShift: Login to IronShift"** from the Command Palette
2. You'll be redirected to the **[IronShift Dashboard](https://app.ironshift.dev)** in your browser
3. Sign up or sign in (via email, Google, or GitHub)
4. The token is automatically sent back to **your IDE** via the correct URI scheme (`vscode://`, `cursor://`, `windsurf://`, etc.)
5. Your plan, usage limits, and available models are automatically synced

✅ **IDE-aware OAuth** — Detects your IDE automatically, redirects the token to the right place  
✅ **Multi-IDE support** — Same account, same plan, works in VS Code, Cursor, Windsurf  
✅ **Seamless login** — Google & GitHub OAuth, no manual token copying needed  
✅ **Token-based auth** — Securely stored in the IDE's global state  
✅ **Auto-refresh** — User data syncs periodically to reflect plan changes  
✅ **Logout anytime** — Run **"IronShift: Logout from IronShift"**  

---

## **Commands**

All commands are available via the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`):

| Command | Description |
|---------|-------------|
| **IronShift: Open IronShift** | Open and focus the IronShift chat panel |
| **IronShift: New Chat** | Start a fresh chat session |
| **IronShift: Clear Chat Session** | Clear the current chat session |
| **IronShift: Manage Workspace Context** | Edit the persistent workspace context file |
| **IronShift: Login to IronShift** | Open the IronShift dashboard to sign in |
| **IronShift: Login with Token** | Paste an authentication token manually |
| **IronShift: Logout from IronShift** | Log out and clear stored credentials |
| **IronShift: Deploy Project** | Trigger a cloud deployment for the current project |

---

## **Keyboard Shortcuts**

| Action | Windows/Linux | Mac |
|--------|---------------|-----|
| Open IronShift | `Ctrl+Shift+P` → "Open IronShift" | `Cmd+Shift+P` → "Open IronShift" |
| Send Message | `Enter` | `Enter` |
| New Line | `Shift+Enter` | `Shift+Enter` |
| Paste Image | `Ctrl+V` | `Cmd+V` |

---

## **Supported Tools & Operations**

IronShift works with any CLI tool. Here are some common examples:

### **Cloud Providers**

| Provider | Example Operations |
|----------|--------------------|
| **Azure** | VMs, AKS, Storage, App Services, Monitor, Advisor, Application Insights |
| **AWS** | EC2, S3, Lambda, ECS/EKS, IAM, CloudWatch, Cost Explorer |
| **GCP** | Compute, GKE, Cloud Storage, Cloud Functions |

### **DevOps & Infrastructure Tools**

| Tool | Example Operations |
|------|--------------------|
| **Docker** | Build, Run, Manage containers and images |
| **Kubernetes** | Pods, Deployments, Services, Namespaces, HPA |
| **Terraform** | Plan, Apply, State management, IaC generation |
| **Ansible** | Playbook generation, Server configuration |

---

## **Configuration**

| Setting | Default | Description |
|---------|---------|-------------|
| `ironshift.backendUrl` | IronShift Cloud | Backend API URL (for enterprise/self-hosted deployments) |
| `ironshift.dashboardUrl` | `https://app.ironshift.dev` | URL of the IronShift web dashboard for authentication |
| `ironshift.autoApprove` | `false` | Auto-approve low-risk read operations without confirmation |
| `ironshift.defaultModel` | `gpt-5.2` | Default AI model for chat responses (see available models above) |

---

## **Plans & Pricing**

IronShift uses a **credit-based system** — credits represent your actual AI API budget, giving you full transparency and flexibility.

> 💡 **1 credit = $0.01** — Credits are consumed based on the tokens used by each AI model call.

| | **Starter** | **Pro** *(Most Popular)* | **Pro Plus** |
|---|---|---|---|
| **Price** | Free | $10/mo | $20/mo |
| **Credits/Month** | 30 | 600 | 1,200 |
| **Standard models** (GPT-5.2, Gemini 2.5, Grok 4, Auto Free) | ✅ | ✅ | ✅ |
| **Premium models** (GPT-5.4, Claude Sonnet 4.6/4.5, Gemini 3, Auto Pro) | 🔒 | ✅ | ✅ |
| **Top-tier models** (GPT-5.4 Pro, Claude Opus 4.6/4.5) | 🔒 | 🔒 | ✅ |
| **All operation modes** (Chat, Plan, Agent) | ✅ | ✅ | ✅ |
| **Image attachments & vision** | ✅ | ✅ | ✅ |
| **Local chat history** | ✅ | ✅ | ✅ |
| **Terminal Auto-Fix** | ✅ | ✅ | ✅ |
| **IaC File Generator** | ✅ | ✅ | ✅ |

- No credit card required for the free plan
- Cancel anytime
- Monthly & yearly billing available

Upgrade anytime from the **[IronShift Dashboard](https://app.ironshift.dev)**. Plan changes sync automatically to your extension.

---

## **Security & Privacy**

IronShift is built with security and privacy as top priorities.

✅ **Privacy-First** — Chat history stored locally, never sent to cloud  
✅ **Credentials Stay Local** — Uses your existing CLI authentication  
✅ **Human-in-the-Loop** — All write operations require explicit approval  
✅ **Audit Trail** — Every action logged in conversation history  
✅ **Enterprise Ready** — Self-host your own backend for complete control  
✅ **No Data Collection** — Your queries and results stay on your machine  
✅ **Secure Auth** — OAuth via Google & GitHub, JWT-based token storage  

---

## **Roadmap**

We're constantly improving IronShift. Here's what's coming:

- [x] ✅ **Auto Mode** — Intelligent multi-model selection per task
- [x] ✅ **Terminal Auto-Fix** — AI fixes failed commands instantly
- [x] ✅ **IaC File Generator** — Terraform, Ansible, Kubernetes wizard
- [x] ✅ **Credit-based usage** — Transparent, token-based billing
- [ ] ⏰ **Scheduled operations** and automation workflows
- [ ] 👥 **Team collaboration** features
- [ ] 🔧 **Custom tool definitions** for enterprise needs

---

## **Support, Feedback & Community**

We're constantly improving **IronShift** to make your cloud operations even better. Your feedback helps shape the future of the extension!

💬 **[Join the Conversation](https://discord.com/invite/ZvYYKcJYE9)** — Connect with fellow developers, share feedback, and get real-time support in our active **Discord Community**.  
🐞 **[Report Issues & Suggestions](https://github.com/Clavel-AI/IronShift-Assistant/issues)** — Found a bug or have a feature request? Let us know—we're always listening.  
💡 **[Feature Requests](https://github.com/Clavel-AI/IronShift-Assistant/discussions)** — Share your ideas and vote on upcoming features.  
📧 **Email:** support@ironshift.dev  
🌐 **Website:** [https://ironshift.dev](https://ironshift.dev)  
📢 **[Join our Reddit Community](https://www.reddit.com/r/Ironshiftofficial/)** — Discuss features, share ideas, and engage with the IronShift team.

We're excited to have you on board—let **IronShift** supercharge your cloud workflow! 🚀

---

## **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ by the <strong>IronShift Team</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Install%20Now-VS%20Code%20Marketplace-007ACC?style=for-the-badge" alt="Install Now">
  </a>
</p>
