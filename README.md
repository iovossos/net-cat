# net-cat

`net-cat` is a simple TCP chat server implemented in Go, inspired by the functionality of the traditional Netcat tool. It allows multiple clients to connect and communicate with each other over a network.

## Features

- Accepts multiple client connections
- Broadcasts messages to all connected clients
- Graceful handling of client disconnections

## Installation

1. Ensure you have [Go](https://golang.org/dl/) installed on your system.
2. Clone the repository:

   ```bash
   git clone https://github.com/iovossos/net-cat.git
   ```

3. Navigate to the project directory:

   ```bash
   cd net-cat
   ```

4. Build the project:

   ```bash
   go build -o net-cat
   ```

## Usage

1. Start the server:

   ```bash
   ./net-cat
   ```

   By default, the server listens on `localhost:8080`.

2. Connect to the server using a TCP client like Netcat:

   ```bash
   nc localhost 8080
   ```

   You can open multiple terminal windows and run the above command to simulate multiple clients.

3. Type messages in the client terminal and press Enter to send. Messages from other clients will be displayed in your terminal.

## Authors

1. [iovossos](https://github.com/iovossos)
2. [ustikker](https://github.com/stikkeruip)
3. [arsentsn](https://github.com/arsentsn)