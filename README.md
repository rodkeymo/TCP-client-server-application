# TCP-client-server-application
Sockets and the socket API are used to send messages across a network. They provide a form of inter-process communication (IPC). The network can be a logical, local network to the computer, or one that’s physically connected to an external network, with its own connections to other networks. The obvious example is the Internet, which you connect to via your ISP.


The Server Socket Program here is a Python Console based Application . This program act as a Server and listening to clients request from Port No. 12010

        server.bind((LOCALHOST, PORT))
        server.listen(1)

The Client socket is connected to the Port 8080 of the Python Server Socket Program , and the IP Address ("127.0.0.1") of the server machine.
Here we give as 127.0.0.1 , because the Server and Client running on the same machine. If the client program running on other machine, then you can give the IP Address of that machine.

      client.connect(SERVER, PORT)
