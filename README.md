# Basic message app
this is a basic socket program in C++ that sends a message from a client to a server.

# How it works
-client.cpp:
this cpp file containes the client(the messager part of the program) 
the client sends a message of choice to the server.
-make sure to change "YOUR_PUBLIC_IP" to your friend's public IP adress. and if you want to send it to yourself change it to "127.0.0.1" your local IP adress.

# How to run
the code doesn't work unless you write this command in your terminal (eathier IDE terminal or cmd terminal)
g++ -o client client.cpp lws2_32
this command makes an exe file called "client" (the first cliennt is the name of the exe file made the second client is the name of the cpp file)
after that you run your exe file and send the message to your friends or to yourself.
