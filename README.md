# 🗨️ Local Chat Application in C

A simple **chat application** built in C using **TCP sockets**.  
This project demonstrates the basics of client-server communication, where a server listens on a port and a client connects to exchange messages.

---

## 🚀 Features
- Server and client implemented in pure C  
- Simple text-based chat over TCP  
- Runs locally (`localhost:8080` by default)  
- Great for learning socket programming  

---

## 📂 Project Structure

├── chat_server.c # Server code
├── chat_client.c # Client code
└── README.md # Project documentation

---

## 🛠️ How to Run

1. Compile the server and client code:
```bash
gcc skserver.c -o skserver
gcc skclient.c -o skclient
```

2. Run the server:
```bash
./skserver
```

3. Run the client:
```bash
./skclient
```

---

## 📝 Notes
- This is a basic implementation for educational purposes.  

## License
This project is licensed under the MIT License.
