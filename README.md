
# Code-Sync

A collaborative, real-time code editor where users can seamlessly code together. It provides a platform for multiple users to enter a room, share a unique room ID, and collaborate on code simultaneously.

[![GitHub contributors](https://img.shields.io/github/contributors/sahilatahar/Code-Sync)](https://github.com/sahilatahar/Code-Sync/graphs/contributors) [![GitHub stars](https://img.shields.io/github/stars/sahilatahar/Code-Sync)](https://github.com/sahilatahar/Code-Sync/stargazers) [![GitHub issues](https://img.shields.io/github/issues/sahilatahar/Code-Sync)](https://github.com/sahilatahar/Code-Sync/issues) [![GitHub license](https://img.shields.io/github/license/sahilatahar/Code-Sync)](https://github.com/sahilatahar/Code-Sync/blob/main/LICENSE)

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
- 🚀 **Live Preview**: View the live preview of the project [here](code-sync-live.vercel.app).

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



## 🌟 Appreciation for Resources
Special thanks to **EMKC** for providing the Piston API, enabling code execution. For more information, visit the following links:
- [Piston Repository](https://github.com/engineer-man/piston)
- [Piston Docs](https://engineer-man.github.io/piston-docs/)

Also, huge gratitude to **Tldraw** contributors for their amazing library. For more information about Tldraw, please visit:
- [Tldraw Repository](https://github.com/tldraw/tldraw)
- [Tldraw Documentation](https://docs.tldraw.com/)

## ✍️ About Developer
**Anushka Rakshe**


