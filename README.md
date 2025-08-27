# 💬 ChatRoom

A simple **multi-client chatroom** built with Python sockets and threading.  
Clients connect to a central server, choose nicknames, and exchange real-time messages with join/leave notifications.

---

## 🚀 Features
- Multi-client support using **threads**
- Clients can set **nicknames**
- Broadcasts messages to all connected users
- Join/leave notifications
- Simple, lightweight, and easy to run

---

## 🖥️ Usage

### 1. Start the server
```bash
python3 server.py
2. Run clients (in separate terminals)
bash
Copy code
python3 client.py
3. Chat 🎉
Type messages in one client, and they’ll appear instantly on all clients.

📂 Project Structure
bash
Copy code
ChatRoom/
 ├── client.py    # Client code
 ├── server.py    # Server code
 ├── README.md    # Project documentation
 └── .gitignore   # Ignore virtualenv, pycache, IDE files
🔧 Technologies
Python 3

socket

threading

📸 Demo
Run multiple clients and see messages broadcasted in real-time.

📜 License
This project is for educational/demo purposes. Feel free to use and modify.
