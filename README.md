# MULTITHREADED-CHAT-APPLICATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MAHESHA H N

*INTERN ID*: CT04DK29

*DOMAIN*: JAVA

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION* : The Multithreaded Client-Server Chat Application is developed using Java, leveraging socket programming and multithreading to enable real-time communication between multiple clients. The core components include a server (ChatServer) that listens for incoming client connections and spawns a new thread (ClientHandler) for each connected client. This threading approach allows the server to handle multiple clients concurrently without blocking, enabling real-time message exchange. Each ClientHandler reads messages from its respective client and broadcasts them to all other connected clients, ensuring that everyone in the chat room receives messages instantly.

The application is built using standard Java tools such as JDK for compilation and execution, input/output streams for reading and writing data through sockets, and can be run through a command-line interface. It uses TCP/IP for reliable message delivery and employs a synchronized broadcast mechanism to maintain consistency and thread safety when multiple clients are communicating simultaneously. This project can be used in LAN-based networks for internal team communication and can be extended to include features like private messaging, GUI using Java Swing, or even authentication and persistence using a database. Overall, this application demonstrates the power of Java in building scalable, real-time, networked applications.

*OUTPUT1*:

Chat server started on port 1234
New client connected: Socket[addr=/127.0.0.1,port=56012,localport=1234]
New client connected: Socket[addr=/127.0.0.1,port=56013,localport=1234]
Client disconnected: Socket[addr=/127.0.0.1,port=56013,localport=1234]

*OUTPUT2*:

Connected to chat server!
Hello, I am Client 1
Received: Hello from Client 2!
How are you?
Received: I'm fine! This chat is working well. 😊

*OUTPUT3*:

Connected to chat server!
Received: Hello, I am Client 1
Hello from Client 2!
Received: How are you?
I'm fine! This chat is working well. 😊


