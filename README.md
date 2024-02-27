# Web Socket Project Readme

## Introduction
Welcome to the Web Socket project! This project utilizes WebSocket technology to enable real-time communication between clients via a server. With WebSocket, you can send messages between clients instantaneously without needing to constantly refresh the page.

## Setup
To get started with the project, follow these steps:

1. **Clone the Repository**: 
    ```
    git clone <repository-url>
    ```

2. **Install Dependencies**: 
    ```
    npm install
    ```

3. **Start the Server**: 
    ```
    node app.js
    ```

## Usage
After setting up the project and starting the server, you'll need to open two separate clients, such as two different web browsers (e.g., Chrome, Brave, Firefox, etc.). You can then use these clients to communicate in real-time. Here's how:

1. **Open Two Clients**: Open two separate browser windows or tabs and navigate to the project's URL.

2. **Write and Send Messages**:
   - In one of the clients, write a message in the input field provided.
   - Click on the "Send" button to send the message.

3. **Real-Time Communication**:
   - You'll see the message you sent appear immediately in the other client.
   - Similarly, any messages sent from the second client will be displayed instantly in the first client.

4. **Vice Versa**:
   - The real-time communication works bidirectionally, meaning messages sent from either client will be received by the other client instantly.

## Additional Notes
- Make sure your network allows WebSocket connections.
- If you encounter any issues, ensure that the server is running correctly and that there are no errors in the console.
- Feel free to explore and modify the project as needed. It's a great starting point for building real-time chat applications, collaborative tools, and more.

Enjoy using the Web Socket project for real-time communication! If you have any questions or feedback, feel free to reach out to me at ```kishanmishrawork@gmail.com```.
