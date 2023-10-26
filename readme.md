# Client-Server Communication Project

## Overview

The Client-Server Communication Project is a Python-based demonstration of socket programming, showcasing how a client can establish a connection with a server, send messages, receive responses, and log data in a file. This project is a valuable resource for learning the fundamentals of network communication using Python sockets.

## Table of Contents
- [Client-Server Communication Project](#client-server-communication-project)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [License](#license)

## Features

This project offers several key features:

- **Socket Communication**: It establishes a socket connection between a client and a server, enabling bidirectional communication.

- **Message Exchange**: The client can send messages to the server, which then processes and responds to those messages.

- **Logging**: The received responses are logged in a specified log file, providing a record of interactions for future reference.

## Getting Started

### Prerequisites

Before getting started with this project, make sure you have the following prerequisites in place:

- Python 3.x: You'll need a Python interpreter to run the provided scripts.
- Basic Networking Knowledge: A fundamental understanding of sockets and network communication will be beneficial.

### Installation

To use this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/markow2010/Client-Server-Communication.git

Navigate to the project directory:

   ```cmd
   cd client-server-project
   ```

## Usage

Once you've set up the project, you can start using it:

Run the client with the following command:

    ```py
    python client.py -s <server_ip> -p <port> -l <logfile>
    ```

Replace <server_ip>, <port>, and <logfile> with the appropriate values:

<server_ip>: The IP address of the server you want to connect to.
<port>: The port number to use for the connection.
<logfile>: The name of the log file to save received responses.
If the provided arguments are not formatted correctly, the program will display an error message.

## Project Structure

The project directory contains the following components:

client.py: This Python script is the client component of the project.

diagrams/: This folder holds diagrams used in this README.

README.md: The documentation you are currently reading.

## License

This project is open source and is provided under the MIT License. For full details, see the LICENSE file.

