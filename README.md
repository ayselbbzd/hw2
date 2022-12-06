# README
My code runs as ./server <server-port-number>, ./client <server-ip-address> <server-port-number> <client-port-number>. Since I had problems using vagrant containers, I do not know if it runs on vagrant. I just tested it with server IP address 127.0.0.1 outside of vagrant containers. 

Firstly, I could not implement Go-Back-N. My code simply sends messages from client to server and vice versa without any reliable data transfer. I only tried to implement the window size idea of Go-Back-N. Also, when terminating the process, only the one which enters 2 newline terminates, the other continues to run (it terminates when you enter 2 new lines there).  
