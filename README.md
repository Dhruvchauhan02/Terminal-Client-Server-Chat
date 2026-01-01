# 💬 Terminal-Based Client–Server Chat System

A terminal-based multi-client chat application built using Python socket programming and threading.  
The project follows a client–server architecture where multiple clients can connect to a central server and exchange messages in real time.

---

## 🚀 Features
- Client–server architecture
- Supports multiple clients simultaneously
- Real-time message broadcasting
- Nickname-based chat
- Multithreading for concurrent communication
- Terminal (CLI) based interaction

---

## 🛠 Tech Stack
- Python
- Socket Programming (TCP)
- Threading

---

## 📂 Project Structure
Terminal-Client-Server-Chat/
├── server.py
├── client.py
├── README.md
└── .gitignore


---

## ⚙️ How It Works
- The server listens on a specific IP address and port.
- Clients connect to the server using the server’s IP and port.
- Each connected client is handled in a separate thread.
- Messages sent by a client are received by the server and broadcast to all other connected clients.

---

## 🌐 Working on the Same Wi-Fi Network

By default, the server may be configured like this:

HOST = '127.0.0.1'
This allows only the same device (localhost) to connect.

✅To allow other devices on the same Wi-Fi network to connect:

Change the HOST value in server.py to:

HOST = '0.0.0.0'

This allows the server to accept connections from any device on the same local network (LAN).

Clients can then connect using the server device’s local IP address (e.g., 192.168.x.x).

▶️ How to Run the Project
1️⃣ Start the Server
On the server device:
python server.py

2️⃣ Start the Client
python client.py


## ✅ This version is:
✔ Clean  
✔ Minimal  
✔ Portfolio-ready  
✔ Clearly explains same Wi-Fi behavior  
✔ Stops exactly where you wanted  

You can now **commit and push** this README safely.

If you want next:
- Even shorter README (very minimal)
- README for another project
- Help uploading the next repo

Just tell me 👍
