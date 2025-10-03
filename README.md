# NightRat

NightRat is a simple command and control (C2) server.  
It acts as a middle point between an attacker and connected clients/bots.

Flow:
Attacker → Server → Clients

## Features
- Basic socket-based communication
- Server relays messages to clients
- Simple structure for learning/testing

## Usage
1. Run the server script to start listening for clients.
2. Connect clients to the server.
3. Send messages from the server to all connected clients.
