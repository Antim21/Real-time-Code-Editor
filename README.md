# Real-time-Code-Editor

Developed an online tool enabling collaborative code writing, editing, and review for multiple users using JavaScript.
Integrated support for multiple programming languages with syntax highlighting and version tracking.
Implemented communication features to enhance team collaboration and productivity

You can visit here
https://codebuddytextedit.netlify.app/

A web-based real-time collaborative code editor that allows multiple users to write, edit, and view code simultaneously. This project supports syntax highlighting for various programming languages, live updates across users, and an intuitive UI. It uses WebSockets for real-time communication, enabling seamless collaboration similar to platforms like Google Docs or VS Code Live Share.

Features
Real-Time Collaboration: Multiple users can edit the same code simultaneously, with changes reflected in real-time across all connected users.

Syntax Highlighting: Supports syntax highlighting for multiple programming languages (e.g., JavaScript, C++) for better readability and editing.
Multi-User Support: Seamless communication and synchronization between users using WebSockets.

Code Sharing: Users can share code sessions with others using a unique session link.

Customizable Themes: Dark and light mode themes for a better coding experience.

Live Preview: Displays output of code in real-time for supported languages.

Undo/Redo Functionality: Allows users to easily undo or redo changes while editing.
Tech Stack
Frontend: React.js, CSS, HTML

Backend: Node.js, Express.js

WebSocket Protocol: Socket.IO for real-time communication

Code Parsing: Integrated with Ace Editor or CodeMirror for code editing

Database: MongoDB (for storing user session and code history)
