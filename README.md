# ctp
Chat Transfer Protocol: The next level in chat speed
# The gist of the process: Modes
## Mode 1: Handshake
Here is the conversation between the client with IP 192.168.0.0 and username Bob, and the server with IP 127.0.0.1.

Client: "Hello! I am 192.168.0.0, but you can call me Bob. Let all your other friends know, ok?"

Server (to other clients): "Call 192.168.0.0 Bob, ok?"

Other clients: "Okay!"

Server (to main client): "Done! You are connected!"

## Mode 2: Normal relay
Client: "Hi, can you tell everyone 'This is my first post!'?"

Server: "Sure! (to others) 192.168.0.0 said 'This is my first post!'"

Other clients: "Got it! (to themselves) That's Bob."
