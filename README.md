# Socket ChatAPP.
- This project is a real-time messaging system developed using Java Sockets. It implements a robust Client-Server model capable of handling multiple simultaneous connections.
## ​Technical Implementation:
- ​Technology Stack: Core Java (java.net.Socket, java.net.ServerSocket).
- ​The Server: Initializes a ServerSocket to listen on a designated port. It uses multi-threading to handle incoming connections, ensuring that multiple users can chat simultaneously without blocking the server.
- ​The Clients: Java programs that instantiate a Socket to connect to the server's IP and port.
## ​Testing & Environment Independence:
To demonstrate the stability of the socket connections and the independence of the client processes, the system was tested in a simulated distributed environment on a single machine:
- ​Client A: Executed via NetBeans.
- ​Client B: Executed via VS Code.
- ​Client C: Executed via Command Prompt/Terminal.
​This setup confirms that the socket communication logic functions correctly regardless of the execution environment or IDE.
