# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

**COMPANY**:CODTECH IT SOLUTIONS

**NAME**:MONISH G

**INTERN ID**:CT08IWZ

**DOMAIN**:WEB DEVELOPMENT

**BATCH DURATION**:JANUARY 5th,2025 to FEBRUARY 5th,2024

**MENTOR NAME**: NEELA SANTHOSH

**DESCRIPTION**
                                                       **Real-Time Collaborative Document Editor**
Overview

The Real-Time Collaborative Document Editor is a dynamic web application that allows multiple users to create, edit, and share documents simultaneously. Designed for efficiency and teamwork, the editor ensures seamless collaboration with real-time updates and secure access for users.

Features

Real-Time Collaboration: Instant synchronization of edits across multiple users with minimal latency using WebSockets.
User Authentication: Secure login and user management with JWT (JSON Web Token) for data integrity and confidentiality.
Rich Text Editing: A user-friendly text editor with essential formatting tools.
Scalable Backend: Built on NestJS, the server efficiently handles concurrent users and ensures high availability.
Responsive Design: Tailored for desktop and mobile devices using TailwindCSS for a sleek, responsive UI.
Robust State Management: Context API ensures efficient state handling on the frontend.
Persistent Data: Document data is stored securely in MongoDB Atlas, ensuring availability and durability.
Collaboration Awareness: Visual indicators show who is currently editing or viewing the document.
Change Conflict Resolution: Handles simultaneous edits with intelligent conflict resolution algorithms.
Customizable: Built with modular and reusable components for easy customization and feature addition.


Tech Stack

Frontend

ReactJS: Handles the dynamic rendering of the user interface.
Context API: Manages state globally for a seamless user experience.
TailwindCSS: Provides responsive and visually appealing styles for the editor.

Backend

NestJS: A modular and scalable framework for building the server-side application.
WebSockets Gateway: Enables real-time communication between the server and clients.
Socket.io: Ensures efficient bi-directional communication for real-time updates.
Mongoose: ORM for seamless interaction with MongoDB.
MongoDB Atlas: Cloud-based database for storing user and document data securely.
JWT (JSON Web Token): Implements secure authentication using HMAC with SHA-256.
TypeScript: Provides type safety and improved maintainability across the application.


Installation

Clone the repository:

git clone https://github.com/your-repo.git  
cd real-time-editor  

Install dependencies for both frontend and backend:

# Frontend  
cd frontend  
npm install  

# Backend  
cd backend  
npm install  

Configure environment variables:

Create .env files in both frontend and backend directories.
Add your MongoDB Atlas URI, WebSocket configurations, and JWT secret key.
Run the application:

# Frontend  
npm start  

# Backend  
npm run start:dev  
Open your browser and navigate to http://localhost:3000 (or the specified frontend port).

Future Enhancements
Offline editing with automatic synchronization.
Integration with third-party cloud storage (Google Drive, Dropbox, etc.).
Advanced formatting and document versioning.
Support for multimedia content (images, videos).

OUTPUT:

![Image](https://github.com/user-attachments/assets/9736de69-e124-4c60-8e2d-f989e036c275)

![Image](https://github.com/user-attachments/assets/0420bb57-7938-4a73-a36d-3f412b732fb9)

![Image](https://github.com/user-attachments/assets/799336a1-2c83-4672-a583-112a98d52b31)
