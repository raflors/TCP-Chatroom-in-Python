# Introduction

In this simple program, I implemented a simple fully-functioning TCP chat room with GUI using Python and Tkinter. It has one server that hosts the chat and multiple
clients that connect to it and communicate with each other.

This is a very basic program that I made for CS50 as my final project and which will be updated when I can. In the near future, I will include banning, kicking and file transfering.
But for now, let's all stick to the simplicity of this program.

## How to run the program

Run the ```bash server.py``` from the command line

Input usage: ```python3 server.py <host> [-p PORT]```
    host: Can be a hostname, or an IP address.
    -p port: TCP port the server listens at (default 1060)

    e.g.
    ```bash $ python3 server.py 127.0.0.1
            Listening at ('127.0.0.1', 1060)```

Run the ```bash client.py``` in separate terminal window, just like running the server.py

Run another multiple terminals and run ```bash client.py``` and chat real time. A Tkinter GUI will pop up!


## Future updates

Kicking, Banning and file transfer will be added when I can! So feel free to check out my [pip](https://github.com/raflors) for updates!
