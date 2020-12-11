# TCP-Chatroom-in-Python
Simple TCP chat room using Python

Python Multi-person Internet Chat Room
A small chat room program written in Python 3, that allows multiple people to instant messaging over the internet.

Usage

Run server.py on the machine you wish to act as the server, entering the desired port you wish to run the server on. You can run multiple independent servers, however they must be running on different ports.
Any clients can now connect to the server by running client.py then entering the IP and port the server is running on (as seen in the server terminal). Clients can choose a username and then send messages by entering them into the Python terminal. Messages from other clients will be printed to the Python terminal.

Know Issues

While using the program as a client, if you are typing a message and receive one at the same time, you may experience some errors with the received message interrupting the message you are typing. Unfortunately, this is unfixable currently due to Python 3 having issues with printing and accepting user input at the same time.

Requirements
Python 3
Socket Module (standard library)
Threading Module (standard library)
