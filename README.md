# Python_Chat_Bot
# 🔐 Encrypted Chat Room (Python)

A simple Python-based **multi-client chatroom** with optional **shared-room-code encryption**.  
Built with `socket` and `threading`, this project allows multiple clients to connect to a server and chat securely over the same Wi-Fi or LAN.

---

## ✨ Features
- 🖥️ **Multi-client support** (server can handle many users at once)
- 🔑 **Room code encryption** (only people with the correct code can join)
- 🌐 **LAN / Wi-Fi support** (chat with friends on the same network)
- 🧩 **Simple design** – just Python sockets, no heavy frameworks
- ⚡ **Real-time messaging** using threads

---

## 🛠️ Requirements
- Python 3.8+  
- Works on Windows, Linux, MacOS

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/rutikavhad/Python_Chat_Bot.git
cd Python_Chat_Bot

```
### 2. How To Run
-1 : First run this chatserver.py file
-This is main server of this chat bot 
```bash
chatserver.py
```
-2.This is client file you can run any client server to connect to server
-before this must change ip of this code 
-open client.py in any text editor 
-_if windows :In Terminal Type *ipconfig* -look for IPv4 Address : look for :client.connect(('..*..',55555))_
```bash
ipconfig
```
-_if linux/mac :In Terminal Type *ifconfig* - look for  inet     : look for :client.connect(('..*..',55555))_
```bash
ifconfig
```

#After done this all run chatclient.py
```bash
chatclient.py
```
