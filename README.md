<h1 align="center">💻 Code-Sync - Real-Time Collaborative Code Editor</h1>
<p align="center">A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.</p>

<div align="center">
    <img src="preview.png" alt="Code-Sync Preview" width="80%">
</div>



## 🔮 Features
- 💻 Real-time collaboration on code editing across multiple files
- 📁 Create, open, edit, save, delete, and organize files and folders
- 💾 Option to download the entire codebase as a zip file
- 🚀 Unique room generation with room ID for collaboration
- 🌍 Comprehensive language support for versatile programming
- 🌈 Syntax highlighting for various file types with auto-language detection
- 🚀 Code Execution: Users can execute code directly within the collaboration environment for instant feedback and results
- ⏱️ Instant updates and synchronization of code changes across all files and folders
- 📣 Notifications for user join and leave events
- 👥 User presence list of users currently in the collaboration session, including online/offline status indicators
- 💬 Group chatting for real-time communication while coding
- 🎩 Real-time tooltip displaying users currently editing
- 💡 Auto-suggestions based on the programming language
- 🔠 Option to change font size and font family
- 🎨 Multiple themes for a personalized coding experience
- 🎨 Collaborative Drawing: Allowing real-time collaborative sketching


## 💻 Tech Stack
- **Frontend**: React, TypeScript, React Router, Tailwind CSS
- **Backend**: Node.js, Express.js, Socket.io
- **Deployment**: Git, GitHub, Vercel

## ⚙️ Installation

1. **Fork this repository**: Click the **Fork** button in the top-right corner to fork the repository.

2. **Clone the repository**:
   ```bash
   git clone https://github.com/<your-username>/Code-Sync.git
   ```

3. **Set .env file**: Inside the `client` and `server` directories, rename `.env.example` to `.env` and set the environment variables:
   - **Frontend**:
     ```bash
     VITE_BACKEND_URL=<your_server_url>
     ```
   - **Backend**:
     ```bash
     PORT=3000
     ```

4. **Install dependencies**: Navigate to the frontend and backend directories separately and run:
   ```bash
   npm install
   ```

5. **Start the frontend and backend servers**:
   - **Frontend**:
     ```bash
     cd client
     npm run dev
     ```
   - **Backend**:
     ```bash
     cd server
     npm run dev
     ```

6. **Access the application**: Open a browser and go to [http://localhost:5173/](http://localhost:5173/)

## 🔮 Features for Next Release
- **Admin Permission**: Implement an admin permission system to manage user access levels and control platform features.

## 🤝 Contribute
We welcome contributions to make Code-Sync even better! Whether you're reporting a bug, suggesting a new feature, or fixing a typo, your input is valuable to us. Follow the contribution guidelines to get started.

## 🌟 Support Us
If you find this helpful or valuable, please consider 🌟 starring the repository. It helps us gain visibility and encourages further development. We appreciate your support!


## ✍️ About Developer
**Anushka Rakshe**


