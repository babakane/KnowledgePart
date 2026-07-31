# 🤖 KnowledgePart - AI-Powered Online Chatbot

An intelligent, feature-rich web-based chatbot application built with modern web technologies. KnowledgePart provides real-time AI conversations with support for multiple language models and advanced code analysis capabilities.

---

## ✨ Features

### 🎯 Core Capabilities
- **Real-time AI Conversations** - Seamless chat interface with multiple AI models
- **Multi-Model Support** - Switch between Google Gemini models (Flash, Pro) and offline sandbox mode
- **Code Editor Integration** - Built-in code editor with syntax highlighting and line numbering
- **Smart Code Analysis** - AI-powered code review, bug fixing, and documentation generation
- **File Management** - Load repositories, create files, organize project structure
- **Diff Viewer** - Visual comparison of code changes and commits

### 🛠️ Developer Tools
- **Format Code** - One-click code formatting
- **Generate Documentation** - Auto-generate JSDoc/docstrings
- **Fix Issues** - AI-assisted bug detection and fixing
- **Refactor Code** - Intelligent code improvements
- **Unit Test Generation** - Automatic test suite creation
- **Code Explanation** - Understand complex code through AI analysis

### 🔐 Security & Privacy
- **Local API Key Storage** - Credentials stored securely in browser localStorage
- **Offline Mode** - Full functionality without API key using sandbox AI
- **GitHub Integration** - Optional GitHub token support for private repository access
- **No External Data Logging** - Your code stays private

---

## 🚀 Quick Start

### Option 1: Online Demo
Visit the live chatbot at: [**https://babakane.github.io/KnowledgePart/**](https://babakane.github.io/KnowledgePart/)

### Option 2: Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/babakane/KnowledgePart.git
   cd KnowledgePart
   ```

2. **Open in your browser**
   - Simply open `index.html` in any modern web browser
   - No server or build tools required!

3. **Set Up API (Optional)**
   - Get a free Google Gemini API key from [aistudio.google.com](https://aistudio.google.com)
   - Enter your key in the chatbot's API settings
   - Start using advanced Gemini models

---

## 📖 How to Use

### Getting Started
1. **Load a Repository** (Optional)
   - Enter a GitHub repo URL in the sidebar
   - Click "Load" to import files and structure

2. **Start Chatting**
   - Click the chat panel (right side)
   - Type your message or select quick actions
   - Receive AI-powered responses instantly

### Code Analysis Workflow
1. **Open/Paste Code**
   - Load from a file or paste directly into the editor
   
2. **Request Analysis**
   - Choose an action: Explain, Fix, Refactor, or Generate Tests
   - The AI provides detailed suggestions

3. **Apply Changes**
   - Review the AI's output
   - Click "Apply to Editor" to integrate changes

### Working with Files
- **Create Files** - Use "+" File button in sidebar
- **Edit Code** - Full-featured text editor with cursor tracking
- **Commit Changes** - Push updates to GitHub (with token)
- **Switch Branches** - Manage different development branches

---

## 🎨 UI Highlights

### Modern Design System
- **Clean, Minimal Interface** - Distraction-free development experience
- **Dark & Light Themes** - Customizable color scheme
- **Responsive Layout** - Works on desktop, tablet, and mobile
- **Keyboard Shortcuts** - Power user efficiency

### Components
- **Sidebar** - File tree and repository navigation
- **Editor Area** - Multi-tab code editor with toolbar
- **Chat Panel** - AI assistant with message history
- **Diff View** - Side-by-side code comparison
- **Status Indicators** - Real-time connection status

---

## 🔧 Technology Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript (ES6+) |
| **AI Integration** | Google Gemini API |
| **Version Control** | GitHub API |
| **Storage** | Browser localStorage |
| **Fonts** | Syne, JetBrains Mono |

---

## 📋 AI Models Available

### Google Gemini (Requires API Key)
- **Gemini 2.5 Flash-Lite** - Fastest, most cost-efficient
- **Gemini 2.5 Flash** - Best price-to-performance ratio
- **Gemini 2.5 Pro** - Advanced reasoning and complex synthesis

### Offline Mode
- **Sandbox AI** - Free, unlimited local inference (no API needed)

---

## 🔑 API Setup

### Getting a Gemini API Key
1. Visit [aistudio.google.com](https://aistudio.google.com)
2. Sign in with your Google account
3. Click "Get API Key" → "Create new secret key in Google Cloud"
4. Copy your API key
5. Paste into KnowledgePart's settings panel

### Using with Private Repositories
1. Generate a GitHub Personal Access Token: [github.com/settings/tokens](https://github.com/settings/tokens)
2. Enter in the "GitHub token" field in the sidebar
3. Load private repositories as usual

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl/Cmd + P` | Open search |
| `Tab` | Insert 2 spaces in editor |
| `Ctrl/Cmd + /` | Toggle comment (language-aware) |

---

## 🎯 Use Cases

- **Code Review** - Analyze pull requests and catch bugs early
- **Learning** - Understand unfamiliar codebases with AI explanations
- **Refactoring** - Improve code quality and maintainability
- **Documentation** - Auto-generate comprehensive docs
- **Testing** - Create unit tests automatically
- **Debugging** - Get AI assistance identifying issues

---

## 🤝 Contributing

We welcome contributions! Please feel free to:
- Report bugs and issues
- Suggest new features
- Submit pull requests with improvements
- Share feedback and ideas

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🌟 Support & Feedback

- **Report Issues**: [GitHub Issues](https://github.com/babakane/KnowledgePart/issues)
- **Discussions**: [GitHub Discussions](https://github.com/babakane/KnowledgePart/discussions)
- **Documentation**: Check the `docs/` folder for detailed guides

---

## 🚀 Roadmap

- [ ] Dark/Light theme toggle
- [ ] Code syntax highlighting improvements
- [ ] More AI model integrations (Claude, GPT-4, Llama)
- [ ] Real-time collaboration features
- [ ] Browser extension version
- [ ] VS Code plugin
- [ ] Self-hosted deployment guide

---

**Built with ❤️ by the KnowledgePart Team**

*Empowering developers with AI-powered code assistance* 🎯
