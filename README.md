# -React-Chatbot-
A simple chatbot I built while learning the basics of React
This project is a simple, self-contained chatbot interface built using React. The entire application is contained within a single chatbot.html file, making it easy to run and understand the basic principles of a React application, including components, state management, side effects, and event handling.

Features
Interactive Chat Interface: Displays a conversation between a user and a bot.
User and Bot Messages: Distinguishes between user and bot messages with different styling, alignment, and profile icons.
Message Input: Provides an input field for users to type and a "Send" button to submit messages.
Auto-Scrolling: The chat window automatically scrolls to the newest message, ensuring the latest part of the conversation is always visible.
Mock Bot Logic: Integrates with an external chatbot.js script to generate bot responses.
How It Works
The application is built entirely within an HTML file using CDN-hosted libraries, which is great for simple demos and learning.

React & ReactDOM: The core libraries for building the user interface with components.
Babel: Used for in-browser transpilation of JSX (a syntax extension for JavaScript) into regular JavaScript that the browser can understand.
Component-Based Architecture: The UI is broken down into several functional components:
App: The root component that manages the overall application state, specifically the list of chat messages.
ChatMessages: A component responsible for rendering the list of all chat messages. It uses useEffect and useRef to automatically scroll down as new messages are added.
ChatMessage: A presentational component that renders a single message bubble, styled differently based on whether the sender is the 'user' or the 'bot'.
ChatInput: A controlled component that manages the text input field and the "Send" button. It updates the application's state when a new message is sent.
How to Run
Save the chatbot.html file.
Make sure you have user.png and robot.png images in the same directory as the HTML file.
Open chatbot.html in any modern web browser.
Note: This project is intended for educational purposes to demonstrate React concepts in a simple environment. For production applications, it is recommended to use a proper development setup with a build tool like Vite or Create React App, which handles transpilation, bundling, and optimization more efficiently than in-browser transpilation.


