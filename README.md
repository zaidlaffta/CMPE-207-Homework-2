# CMPE-207-Homework-2
TCP socket

Socket programming is a way of connecting two nodes on a network to communicate with each other. One socket(node) listens on a particular port at an IP, in our case it will be the client. While other socket reaches out to the other to form a connection, in our case it is the server. Generally, server forms the listener socket while client reaches out to the server.

In this assignment I used a client and server on two different machines at the same LAN. The client connects to the server at the IP address 192.168.128.6 while the client at reside on the same subnet at 192.168.128.62. Also, I assigned a port number on the higher TCP port numbers available because most of the lower number at taking by other important protocols like SSH and HTTPs just to name a few. 

Once connection established, the server will create a steam socket and will send a message to the client which is listening to incoming messages from the server. Once the message received the client will terminate the connection while the server still waiting for other connection.


