This is an online vote casting system using TCP multithreaded server-client program. The voters will log on from client systems and cast their vote.

The client. and server.c files are provided. Just compile each file using the following command on Linux terminal or Windows Bash and run it (For client, obviously replace the server.c filename with client.c). Make sure the server is running before running any client.

gcc –pthread server.c -o server.out