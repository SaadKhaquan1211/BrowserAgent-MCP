# 🌐 BrowserAgent:  Browse the web using plain English commands, powered by MCP, Playwright, and LLMs.

**BrowserAgent** is a Streamlit app that turns natural language into browser actions.  
Simply tell it what to do *“Go to Wikipedia and summarize the homepage”* — and it does it.  
It uses the **Model Context Protocol (MCP)**, **MCP-Agent**, and **Playwright** to let you browse, click, extract, and explore the web like never before.

---

## ✨ Features

### 💬 Natural Language Control
- Control a real browser using plain English commands  
- Seamless integration with OpenAI or Anthropic LLMs  

### 🌍 Full Browser Navigation
- Visit websites, go back, refresh, and scroll  
- Multi-step command execution through conversation  

### 🖱️ Interactive Actions
- Click buttons, fill forms, type text, and navigate through dynamic pages  

### 🧠 Smart Extraction & Analysis
- Extract, summarize, or analyze webpage content  
- Capture screenshots of specific page elements for visual feedback  

### 🧩 Complex Task Automation
- Chain multiple browser actions in one command  
- Example: “Go to the blog, open the latest post, and summarize it.”  

---

## ⚙️ Setup & Installation

### 🧱 Requirements
- **Python 3.8+**  
- **Node.js & npm** (Playwright dependency – required!)  
  - Download from [nodejs.org](https://nodejs.org)  
- **OpenAI or Anthropic API Key**

---

### 🪜 Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/SaadKhaquan1211/BrowserAgent-MCP.git
   cd BrowserAgent-MCP
Install dependencies

 ```bash

pip install -r requirements.txt
Verify Node.js and npm
 ```
Check npm and node version using below command

 ```bash

node --version
npm --version
 ```
If these commands fail, install Node.js before continuing.

Set your API key

 ```bash


export OPENAI_API_KEY=your-openai-api-key

 ```

▶️ Run the App

Copy code

```bash


streamlit run main.py
Once launched, you’ll see an interface with:

A command input box

A “Run Command” button
```
- Browser feedback and screenshots below

🧩 Example Commands
🔗 Basic Navigation
- Go to www.wikipedia.org

- Go back to the previous page

🖱️ Interaction

- Click the login button
- Scroll down to see more content

📋 Content Extraction

- Summarize the main content of this page

- Extract the navigation menu items

- Take a screenshot of the hero section 

🔄 Multi-step Tasks

- Go to the blog, open the latest post, and summarize it

🏗️ Architecture Overview

- BrowserAgent connects language models with real web browsing through:

- Streamlit → User Interface

- Model Context Protocol (MCP) → Connects LLMs with real tools

- Playwright → Controls a headless browser for automation

- MCP-Agent → Provides an Agentic Framework for tool use

- OpenAI / Anthropic models → Understand and execute user commands

🌟 Use Cases

- Research assistant that browses and summarizes sites

- Automation of repetitive web tasks

- Testing and debugging website navigation

- Teaching and demos of AI browser automation

🤝 Contributing

- Contributions are welcome!
  
- Report bugs or suggest new features

Submit pull requests

Improve documentation or examples
