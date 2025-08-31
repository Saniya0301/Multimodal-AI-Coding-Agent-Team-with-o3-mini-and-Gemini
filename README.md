# 💻 Multimodal AI Coding Agent Team with o3-mini and Gemini

An **AI-powered Streamlit application** that serves as a personal coding assistant, powered by multiple agents built on the **OpenAI o3-mini model** and **Google Gemini**.  

The app supports **multimodal input** – you can upload an image of a coding problem or describe it in text, and the AI will analyze, generate an **optimal solution**, and execute it securely in a sandbox environment.

---

## 🚀 Features
<img width="852" height="474" alt="{00555015-90FC-45CA-A088-31052852816A}" src="https://github.com/user-attachments/assets/abaf4514-7292-41d6-a51a-67c062851962" />


### 🖼️ Multi-Modal Problem Input
- Upload images of coding problems (`.png`, `.jpg`, `.jpeg`)
- Type problems in natural language
- Automatic text extraction from images
- Interactive problem processing

### 🤖 Intelligent Code Generation
- Generates **optimal solutions** with best time/space complexity
- Produces **clean, documented Python code**
- Includes **type hints** and proper documentation
- Handles **edge cases** automatically

### 🔒 Secure Code Execution
- **Sandboxed execution** environment (E2B)
- Real-time execution results
- Error handling with explanations
- **30-second execution timeout** for safety

### 🧩 Multi-Agent Architecture
- **Vision Agent** → Gemini 2.0 Flash (for image-to-text processing)  
- **Coding Agent** → OpenAI o3-mini (for code generation)  
- **Execution Agent** → OpenAI (for execution + result analysis)  
- **E2B Sandbox** → Secure environment for running code  

---


API Keys Required

You need to configure three API keys in the app sidebar:

OpenAI API Key 

Google Gemini API Key  

E2B API Key

---

### 🖥️ Usage

Upload an image of a coding problem OR type your problem description

Click "Generate & Execute Solution"

Review the generated Python solution with documentation

See execution results, including outputs and errors

Explore any generated files from execution


----
###📌 Tech Stack

Streamlit
 – Web UI

OpenAI o3-mini
 – Code generation

Google Gemini
 – Image & vision understanding

E2B Sandbox
 – Secure code execution


###🛡️ Notes

The app runs in sandbox mode for safe execution

A valid internet connection is required for API requests

All three API keys must be provided for full functionality

### 📜 License

This project is licensed under the MIT License.
