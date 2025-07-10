# MCP-Spring-Python-AI: Multi-Protocol Chatbot 🚀  


![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen.svg)  
![Angular](https://img.shields.io/badge/Angular-20.x-red.svg)  
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)  
![NodeJS](https://img.shields.io/badge/NodeJS-18+-green.svg)  

A **Model Context Protocol (MCP)**-based chatbot integrating **Spring Boot (AI + Ollama)**, **Python/NodeJS MCP servers**, and an **Angular frontend**.  

**Author**: [Mousaddak Hatim](https://github.com/Hatimmdk/AI_agent_Mcp_server_ollama.git)  

---

## 📌 Table of Contents  
- [Overview](#-overview)  
- [Key Features](#-key-features)  
- [Architecture](#-architecture)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Technologies](#-technologies)  
- [Configuration](#-configuration)  
- [Testing](#-testing--debugging)  
-

---

## 🌟 Overview  
A modular chatbot demonstrating **MCP protocol** implementation with:  
- **Spring Boot** (SSE-based MCP client/server)  
- **Python/NodeJS** (STDIO-mode MCP tools)  
- **Angular** frontend for interactive chat.
- **Ollama AI Model (Qwen3) ** modèle d’intelligence artificielle qui génère les réponses

---

## ✨ Key Features  
- **Multi-Backend Integration**:  
  - Spring AI + Ollama (Qwen3 model)  
  - Python/NodeJS MCP servers for tool execution.  
- **Real-Time Communication**: SSE for streaming responses.  
- **Agent-Based UI**: Angular frontend with thinking/reply distinction.  
- **Tool Ecosystem**: Stock lookup, file ops, employee info, etc.  

---

## 🏗️ Architecture  

                  |  Angular Frontend    |
                  |  (User Interface)    |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  | Spring Boot MCP      |
                  |  Client / Server     |
                  +----------+----------+
                             |
          +------------------+------------------+
          |                                     |
          v                                     v
+---------------------+             +---------------------+
|  Python MCP Server   |             |  NodeJS MCP Server  |
+---------------------+             +---------------------+

                             ^
                             |
                  +---------------------+
                  |  Ollama AI Model    |
                  |      (Qwen3)        |
                  +---------------------+


---
###  Project Structure

```plaintext
mcp-spring-python-ai/
├── mcp-client/
│   ├── src/
│   │   ├── main/
│   │   │   └── java/
│   │   │       └── net/
│   │   │           └── hatim/
│   │   │               └── mcpclient/
│   │   │                   ├── agents/
│   │   │                   └── controllers/
│   │   └── resources/
│   │       ├── application.properties
│   │       └── mcp-servers.json
│   └── pom.xml
├── mcp-server/
│   ├── src/
│   │   └── main/
│   │       └── java/
│   └── pom.xml
├── mcp-frontend/
│   ├── src/
│   │   └── app/
│   │       ├── app.component.ts
│   │       ├── app.component.html
│   │       └── app.component.css
│   ├── package.json
│   └── angular.json
├── python-mcp-server/
│   ├── server.py
│   ├── main.py
│   └── pyproject.toml
├── Screenshots/
└── README.md

---

#### ⚙️ Installation

### Prerequisites
- [Ollama](https://ollama.ai/) (`ollama pull qwen3`)
- [Node.js 18+](https://nodejs.org/)
- Angular CLI (`npm install -g @angular/cli`)
- [Postman](https://www.postman.com/) (for API testing)

#### Steps:
1. **Clone & Navigate**:
   ```bash
   git clone https://github.com/Hatimmdk/AI_agent_Mcp_server_ollama.git 
   cd mcp-spring-python-ai
   
##### Réalisation:
![postman:](ScreenShots/image3.png)
![localhot:8086 :](ScreenShots/im5.jpg)
![gvhg](ScreenShots/im6.jpg)
![hbjh](ScreenShots/im7.jpg)
![bhjb](ScreenShots/im8.jpg)
![jbhb](ScreenShots/image4.png)



