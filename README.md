# PRODIGY_FS_04

# Real-Time Chat Application

Welcome to the Real-Time Chat Application! This project demonstrates the implementation of a chat application using WebSocket technology for instant and seamless messaging between users. It allows users to create accounts, join chat rooms, initiate private conversations, and exchange messages in real-time.

## Features

- **Real-Time Messaging:** Users can send and receive messages instantly without refreshing the page.
- **User Accounts:** Users can create accounts to personalize their messaging experience.
- **Chat Rooms:** Users can join different chat rooms or start private conversations.
- **Typing Feedback:** Users receive notifications when others are typing a message.
- **Dynamic Client Count:** Displays the total number of connected clients in real-time.

## Technologies Used

- **Frontend:**
  - **HTML:** Structure of the chat interface.
  - **CSS:** Styling the chat interface for an attractive user experience.
  - **JavaScript:** Handling dynamic interactions and WebSocket communication.

- **Backend:**
  - **Node.js:** JavaScript runtime for server-side programming.
  - **Express:** Framework for setting up the server and handling HTTP requests.
  - **Socket.IO:** Library for real-time WebSocket communication.

## Getting Started

To get started with this project, follow the steps below:

### Prerequisites

- **Node.js:** Ensure you have Node.js and npm (Node Package Manager) installed. You can download them from [nodejs.org](https://nodejs.org/).

### Installation

1. **Clone the Repository**

   First, clone the repository to your local machine:
   git clone https://github.com/your-username/your-repository.git
   cd your-repository

2. **Install Dependencies**
   Install the necessary Node.js modules:npm install

3. **Start the Server**

   Start the server using one of the following commands:npm star
   Or directly with Node.js:
   node app.js
   
   By default, the server will run on port `4000`. You can change the port by setting the `PORT` environment variable:
   PORT=5000 npm start
  
5. **Access the Application**

   Open your web browser and navigate to:http://localhost:4000
  
## File Structure

- **`index.html`**: The main HTML file that sets up the chat interface, including the message display area and input forms.
- **`style.css`**: The CSS file containing styles for the chat interface, making it visually appealing.
- **`main.js`**: The JavaScript file that manages client-side interactions, WebSocket communication, and message updates.
- **`app.js`**: The Node.js server file that sets up the Express server and handles WebSocket connections with Socket.IO.
- **`package.json`**: Lists project metadata, dependencies, and scripts.
- **`package-lock.json`**: Ensures consistent dependency versions across different installations.

## Usage

- **Sending Messages:** Type your message in the input field and click the "Send" button or press Enter. Your message will appear in the chat area and be sent to other users.
- **Viewing Messages:** Messages from other users will be displayed in real-time in the message container.
- **Typing Feedback:** When you start typing, a notification will appear indicating that you are typing. This feedback is shown to other users in the chat room.

## Contributing

Contributions to this project are welcome! If you find any bugs or want to add new features, please open an issue or submit a pull request. Follow the standard GitHub workflow for contributions:

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes with clear and concise messages.
4. Push your branch and open a pull request.

## License

This project is licensed under the MIT License. 

