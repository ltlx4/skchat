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
```
.                
|-- .gitignore
|-- LICENSE
|-- README.md
|-- skclient.c
`-- skserver.c
```
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



## Next Steps
- Add support for multiple clients
- Implement a GUI
- Add encryption


## 📝 Notes
- This is a basic implementation for educational purposes.  
- Error handling is minimal.  
- No encryption or authentication.  
- Not suitable for production use.  

---

## License
This project is licensed under the MIT License.
