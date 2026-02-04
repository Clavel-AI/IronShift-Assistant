<h1 align="center">IronShift — AI-Powered Cloud Infrastructure Copilot</h1>

<p align="center">
  <strong>Manage any cloud or DevOps tool through natural conversation—right inside VS Code</strong>
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Version-0.6.6-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Version">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Installs-25+-4CAF50?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Installs">
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=IronShift.ironshift">
    <img src="https://img.shields.io/badge/Rating-5%2F5-FFC107?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Rating">
  </a>
  <a href="https://twitter.com/IronShiftDev">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://discord.gg/ironshift">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="https://linkedin.com/company/ironshift">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</p>

<p align="center">
  <a href="#what-is-ironshift">What is IronShift</a> •
  <a href="#key-features">Features</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#supported-clouds--operations">Clouds</a> •
  <a href="#support-feedback--community">Support</a>
</p>

---

## **What is IronShift?**

**IronShift** is the AI-powered cloud infrastructure copilot that helps SREs and cloud developers manage, troubleshoot, and automate cloud resources—all within **Visual Studio Code**. Stop context-switching between your IDE, cloud consoles, and documentation.

> Just ask IronShift what you need, and it will execute cloud operations, analyze infrastructure, and provide intelligent recommendations—with your approval.

### **With IronShift, you get:**

✅ **Natural Language Interface** — Ask questions in plain English, no CLI memorization needed  
✅ **Universal Tool Support** — Azure, AWS, GCP, Docker, Terraform, Kubernetes, and more  
✅ **Human-in-the-Loop Safety** — Every action reviewed before execution, you stay in control  
✅ **Multiple AI Models** — Choose from GPT-4.1, Claude, Gemini, Grok, or let Auto mode decide  
✅ **Real-Time Streaming** — Watch as IronShift analyzes and executes step-by-step  
✅ **Vision Support** — Attach screenshots for context-aware troubleshooting  

Designed for **SREs, DevOps engineers, and cloud developers**, IronShift helps you operate cloud infrastructure smarter, faster, and more securely. 🚀

<p align="center">
  <img src="assets/Video%20Project%20(3).gif" alt="IronShift Demo" width="800">
</p>

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

### **Cost Optimization on AWS**

Analyze costs, identify savings opportunities, and optimize your AWS spending—all through natural conversation.

<p align="center">
  <img src="assets/Demo%203.gif" alt="AWS Cost Optimization Demo" width="800">
</p>

✅ **Query AWS costs** — Get instant insights on your cloud spending  
✅ **Identify savings** — Find underutilized resources and optimization opportunities  
✅ **Natural workflow** — Ask questions like "What are my top spending services?"  

---

### **Observability & Monitoring on Azure**

Analyze logs, monitor application health, and get deep insights with Application Insights—right from your IDE.

<p align="center">
  <img src="assets/Demo%204.gif" alt="Azure Observability Demo" width="800">
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
  <img src="assets/feature-approval.png" alt="Action Approval" width="800">
</p>

✅ **See the exact command** — Full transparency on what will run  
✅ **Review all parameters** — Understand every argument before execution  
✅ **Risk assessment** — Know the impact of each operation  
✅ **Approve, modify, or reject** — Complete control at every step  

---

### **7 Industry-Leading AI Models**

Choose from the best AI models across multiple providers, or let Auto mode select the optimal model for each task.

| Model | Provider | Best For |
|-------|----------|----------|
| **GPT-4.1** | OpenAI | Complex reasoning & troubleshooting |
| **GPT-4o** | OpenAI | Fast, high-performance responses |
| **Claude Sonnet 4.5** | Anthropic | Detailed analysis & explanations |
| **Claude Sonnet 4** | Anthropic | Balanced performance |
| **Gemini 2.5 Pro** | Google | Advanced reasoning & multimodal tasks |
| **Gemini 2.5 Flash** | Google | Speed-optimized responses |
| **Grok 4** | xAI | Real-time knowledge & creative solutions |

---

### **Auto Mode — Intelligent Model Selection**

Let IronShift choose the optimal model for each task automatically.

✅ **Command Generation** — Uses best-in-class models for accurate CLI commands  
✅ **Analysis & Reasoning** — Leverages advanced models for complex troubleshooting  
✅ **Fast Responses** — Switches to speed-optimized models for quick queries  
✅ **Toggle anytime** — Switch between Auto and manual model selection  

*No API key management needed—just enable Auto mode and let IronShift handle the rest.*

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

1. Open **Visual Studio Code**
2. Go to **Extensions** (`Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for **"IronShift"**
4. Click **Install**

Or install directly:
```
ext install IronShift.ironshift
```

### **Prerequisites**

| Requirement | Version | Purpose |
|-------------|---------|----------|
| **VS Code** | v1.85.0+ | IDE |
| **Any CLI** | Latest | Cloud/DevOps operations |

IronShift works with any CLI tool you have installed. Common examples:
- **Azure CLI** (`az`) — Azure operations
- **AWS CLI** (`aws`) — AWS operations  
- **gcloud CLI** — GCP operations
- **Docker** — Container management
- **kubectl** — Kubernetes operations
- **Terraform** — Infrastructure as Code

### **Getting Started**

1. Click the **IronShift** icon in the Activity Bar
2. Authenticate with your cloud provider when prompted
3. Start asking questions in natural language!

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
| **Azure** | VMs, AKS, Storage, App Services, Monitor, Advisor |
| **AWS** | EC2, S3, Lambda, ECS/EKS, IAM, CloudWatch |
| **GCP** | Compute, GKE, Cloud Storage, Cloud Functions |

### **DevOps & Infrastructure Tools**

| Tool | Example Operations |
|------|--------------------|
| **Docker** | Build, Run, Manage containers and images |
| **Kubernetes** | Pods, Deployments, Services, Namespaces |
| **Terraform** | Plan, Apply, State management |

---

## **Configuration**

| Setting | Default | Description |
|---------|---------|-------------|
| `ironshift.backendUrl` | IronShift Cloud | Backend service URL (enterprise deployments) |
| `ironshift.autoApprove` | `false` | Auto-approve low-risk read operations |
| `ironshift.defaultModel` | `Auto` | Default AI model for responses |

---

## **Security & Privacy**

IronShift is built with security and privacy as top priorities.

✅ **Privacy-First** — Chat history stored locally, never sent to cloud  
✅ **Credentials Stay Local** — Uses your existing CLI authentication  
✅ **Human-in-the-Loop** — All write operations require explicit approval  
✅ **Audit Trail** — Every action logged in conversation history  
✅ **Enterprise Ready** — Self-host your own backend for complete control  
✅ **No Data Collection** — Your queries and results stay on your machine  

---

## **Roadmap**

We're constantly improving IronShift. Here's what's coming:

- [ ] ⏰ **Scheduled operations** and automation workflows
- [ ] 👥 **Team collaboration** features
- [ ] 🔧 **Custom tool definitions** for enterprise needs

---

## **Support, Feedback & Community**

We're constantly improving **IronShift** to make your cloud operations even better. Your feedback helps shape the future of the extension!

💬 **[Join the Conversation](https://discord.gg/ironshift)** — Connect with fellow developers, share feedback, and get real-time support in our active **Discord Community**.  
🐞 **[Report Issues & Suggestions](https://github.com/Clavel-AI/IronShift-Assistant/issues)** — Found a bug or have a feature request? Let us know—we're always listening.  
💡 **[Feature Requests](https://github.com/Clavel-AI/IronShift-Assistant/discussions)** — Share your ideas and vote on upcoming features.  
📧 **Email:** support@ironshift.dev  
🌐 **Website:** [https://ironshift.dev](https://ironshift.dev)

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
