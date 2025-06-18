# Multithreaded Chat Application

## Company  
**CODTECH IT SOLUTIONS PVT. LTD**

## Intern Details  
**Name:** Nimish Sadhu  
**Intern ID:** CT08DK421  
**Domain:** Java Programming  
**Batch Duration:** April 20th, 2025 – June 20th, 2025  
**Mentor:** Neela Santhosh Kumar  

## Internship Task 3 – Multithreaded Chat Application

### About the Task  
This project was developed as part of my Internship Task 3. The main goal was to build a **Multithreaded Client-Server Chat Application** using Java’s networking and multithreading capabilities. It demonstrates how multiple clients can connect to a single server and exchange messages in real-time through a shared chatroom.

At its core, this application creates a communication channel where a server handles multiple client connections simultaneously by spawning a separate thread for each. This design ensures smooth, concurrent messaging without interruptions or delays for individual users.

### Tools and Technologies Used  
- **Java:** Used to implement socket programming and thread handling. Core classes include `Socket`, `ServerSocket`, `BufferedReader`, and `PrintWriter`.  
- **IntelliJ IDEA:** My primary IDE for writing, testing, and debugging the application. Its built-in tools made it easier to manage multiple classes and run both server and client instances.  
- **ChatGPT:** Assisted in understanding multithreading, socket communication, and best practices for real-time chat systems. Also helped troubleshoot bugs and improve code structure.  
- **YouTube:** Used for watching tutorials and visualizing concepts related to Java networking and multithreading.  
- **Google:** Referred to Java documentation and Stack Overflow for real-world examples, common error fixes, and deeper insight into client-server architectures.

### How It Works  
- The **ChatServer** starts and listens on a specific port (e.g., 12345).  
- Each time a **ChatClient** connects, the server accepts the connection and spawns a new thread dedicated to that client.  
- Clients are prompted to enter their name, after which they can start chatting.  
- Any message sent by a client is broadcast by the server to all other connected clients.  
- Messages are tagged with the sender’s name and appear live in the chat window, simulating a group chat experience.  

It’s a simple terminal-based application, but it effectively mimics the behavior of real-world messaging platforms like WhatsApp or Discord — on a basic level.

### Applications and Use Cases  
- **Real-Time Messaging Systems:** The foundational logic behind many chat platforms (Slack, Teams, etc.)  
- **Live Customer Support Tools:** Can be extended to backend communication in customer support interfaces.  
- **Collaborative Software:** Real-time communication in team or project management tools.  
- **Educational Projects:** A great learning exercise for understanding threads, sockets, and concurrent programming in Java.  
- **Foundation for Advanced Tools:** Can evolve into apps using WebSockets, asynchronous I/O, or frameworks like Netty, Spring Boot, or even Socket.IO (JavaScript).

### Conclusion  
Task 3 was one of the most challenging and rewarding parts of my internship. It allowed me to apply what I’ve learned about **networking, multithreading, and real-time data handling** in Java. With help from tools like IntelliJ, ChatGPT, YouTube, and Google, I was able to overcome errors, debug complex flows, and deliver a working chat system.

This project not only sharpened my Java programming and system design skills but also gave me valuable exposure to real-world software communication patterns — a critical area in backend and full-stack development.
## OUTPUT
![Screenshot 2025-06-18 151605](https://github.com/user-attachments/assets/72cd41b7-2486-4c67-8462-208ab806e24f)
![Screenshot 2025-06-18 151656](https://github.com/user-attachments/assets/6ba02a1d-bc2f-41c9-853b-76a3ac33ae9a)
![Screenshot 2025-06-18 151712](https://github.com/user-attachments/assets/30a34655-33b6-4e52-8d1e-e2d8968c6054)



