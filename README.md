# racketchat
A multiuser TCP/IP based chat server and GUI client program

Usage
-----
To start the server, run 'racket' and evaluate (enter! "server.rkt"). To start the client run 'racket client.rkt'.
By default the server listens on port 1234, and the client connects to 127.0.0.1:1234. 
To change the defaults requires simple changes to the source code. The ip and port the client connects to is specified at the top
of client.rkt, and the listening port for the server is specified at the top of server.rkt.
