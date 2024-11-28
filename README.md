# SyncTalk

A real-time chat platform built specifically for developers and IT professionals. Connect, share code, and discuss technical topics in a developer-friendly environment.

## 🚀 Features

- Real-time messaging with Socket.IO
- Code snippet sharing with syntax highlighting
- Technical rooms based on programming languages/topics
- GitHub integration for profile verification
- Markdown support for technical documentation
- Language-specific code formatting
- Developer-focused user profiles

## 🛠️ Tech Stack

- **Frontend**: Next.js 13+, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express.js, Socket.IO
- **Database**: MongoDB
- **Authentication**: JWT with GitHub OAuth

## 📝 Prerequisites

- Node.js 18+
- MongoDB
- Git

## 🔧 Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/synctalk.git
cd synctalk
```

2. **Set up environment variables**

Create `.env` files in both frontend and backend directories:

```env
# Backend (.env)
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GITHUB_CLIENT_ID=your_github_client_id
GITHUB_CLIENT_SECRET=your_github_client_secret

# Frontend (.env.local)
NEXT_PUBLIC_API_URL=http://localhost:5000
NEXT_PUBLIC_SOCKET_URL=http://localhost:5000
```

3. **Install dependencies**
```bash
# Backend
cd backend
npm install

# Frontend
cd frontend
npm install
```

4. **Run the application**
```bash
# Backend
npm run dev

# Frontend
npm run dev
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

## 📁 Project Structure

```
├── frontend/
│   ├── src/
│   │   ├── app/          # Next.js 13 app router
│   │   ├── components/   # React components
│   │   ├── hooks/       # Custom React hooks
│   │   ├── lib/         # Utilities
│   │   └── types/       # TypeScript types
│   
├── backend/
│   ├── src/
│   │   ├── models/      # MongoDB models
│   │   ├── routes/      # API routes
│   │   ├── config/      # Configurations
│   │   └── socket/      # Socket.IO handlers
```

## 🤝 Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.