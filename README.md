# Nexus Social - Original Social Media Platform

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Node.js](https://img.shields.io/badge/node-%3E%3D16.0.0-green)
![React](https://img.shields.io/badge/react-%3E%3D18.0.0-61dafb)
![MongoDB](https://img.shields.io/badge/mongodb-%3E%3D4.0-green)

## 🌟 Overview

**Nexus Social** is a completely original social media platform built from scratch. It's not a clone of Instagram, Facebook, or any existing platform. Instead, it focuses on:

- **Privacy-first design** - Users control their data and content visibility
- **Content discovery via topics/tags** - Explore interests without algorithmic manipulation
- **Clean & minimal interface** - Unique UI different from mainstream platforms
- **Community-focused** - Meaningful interactions over viral metrics
- **Creative expression** - Share photos, videos, and text in your own way

## ✨ Key Features

### Core Features
- 🖼️ **Photo Sharing** - Upload and organize your visual content
- 🎬 **Short Videos** - Create and share short-form video content
- 📝 **Text Posts** - Share thoughts, updates, and stories
- 👤 **User Profiles** - Customizable profiles with bio, avatar, and cover
- 👥 **Follow System** - Follow users to stay connected
- 🏠 **Interest-based Feed** - Discover content based on topics you care about
- 💬 **Messaging** - Simple, private one-on-one chat
- 🏷️ **Topics & Tags** - Organized content discovery
- 🔒 **Privacy Controls** - Full control over content visibility
- 🌙 **Dark Mode** - Comfortable viewing experience
- 🔍 **Advanced Search** - Find users, content, and topics

### Planned Features
- 📱 Mobile app version
- 🎙️ Voice messages
- 📞 Audio/Video calls
- 🎨 Story creation
- 🌐 Live streaming
- 🤖 Content recommendations (privacy-respecting)
- 📊 Analytics dashboard for creators

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern UI library
- **Tailwind CSS** - Utility-first styling
- **Redux Toolkit** - State management
- **Socket.io Client** - Real-time communication
- **Axios** - HTTP client
- **React Router v6** - Navigation
- **Vite** - Fast build tool

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - ODM
- **JWT** - Authentication
- **Socket.io** - WebSocket support
- **Multer** - File uploads
- **AWS S3** - Cloud storage

## 📁 Project Structure

```
nexus-social/
├── client/                          # React Frontend
│   ├── public/
│   ├── src/
│   │   ├── components/              # Reusable components
│   │   │   ├── Navbar.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   ├── PostCard.jsx
│   │   │   ├── UserCard.jsx
│   │   │   └── ...
│   │   ├── pages/                   # Page components
│   │   │   ├── Home.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── Messages.jsx
│   │   │   ├── Explore.jsx
│   │   │   ├── Login.jsx
│   │   │   └── ...
│   │   ├── hooks/                   # Custom hooks
│   │   ├── context/                 # Context API
│   │   ├── store/                   # Redux store
│   │   ├── services/                # API services
│   │   ├── utils/                   # Utilities
│   │   ├── styles/                  # Global styles
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── index.html
│   ├── tailwind.config.js
│   ├── vite.config.js
│   └── package.json
│
├── server/                          # Node/Express Backend
│   ├── models/                      # Database models
│   │   ├── User.js
│   │   ├── Post.js
│   │   ├── Comment.js
│   │   ├── Message.js
│   │   ├── Topic.js
│   │   └── ...
│   ├── controllers/                 # Route controllers
│   │   ├── authController.js
│   │   ├── userController.js
│   │   ├── postController.js
│   │   ├── messageController.js
│   │   └── ...
│   ├── routes/                      # API routes
│   │   ├── authRoutes.js
│   │   ├── userRoutes.js
│   │   ├── postRoutes.js
│   │   ├── messageRoutes.js
│   │   └── ...
│   ├── middleware/                  # Custom middleware
│   │   ├── auth.js
│   │   ├── errorHandler.js
│   │   ├── validation.js
│   │   └── ...
│   ├── services/                    # Business logic
│   │   ├── authService.js
│   │   ├── socketService.js
│   │   ├── uploadService.js
│   │   └── ...
│   ├── config/                      # Configuration
│   │   ├── database.js
│   │   ├── constants.js
│   │   └── ...
│   ├── utils/                       # Utility functions
│   ├── validators/                  # Input validation
│   ├── app.js
│   ├── server.js
│   └── package.json
│
├── package.json
├── ARCHITECTURE.md
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js >= 16.0.0
- MongoDB >= 4.0 (local or MongoDB Atlas)
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/nexus-social.git
cd nexus-social
```

2. **Setup Backend**
```bash
cd server
npm install
cp ../.env.example ../.env
# Edit .env with your configuration
npm run dev
```

3. **Setup Frontend (in another terminal)**
```bash
cd client
npm install
npm run dev
```

4. **Access the application**
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000

## 🔐 Security Features

- JWT-based authentication with refresh tokens
- Password hashing with bcrypt
- CORS protection
- Rate limiting on API endpoints
- Input validation and sanitization
- HTTPS ready (configure in production)
- Security headers with Helmet
- XSS protection
- CSRF tokens for state-changing operations

## 🎨 Design Philosophy

### Unique Design Aspects
1. **Not a copy** - Original layout and interaction patterns
2. **Privacy-first** - Users control their data
3. **Minimal UI** - Clean, distraction-free interface
4. **Topic-based discovery** - Explore by interests, not algorithm
5. **Mobile-first** - Responsive design from the ground up
6. **Dark mode** - Built-in dark mode support
7. **Accessibility** - WCAG compliant design

## 📝 License

MIT License - see LICENSE file for details

## 🎯 Roadmap

- [x] Project setup and architecture
- [ ] Authentication system
- [ ] User profiles
- [ ] Post creation and feed
- [ ] Messaging system
- [ ] Topic-based discovery
- [ ] Advanced search
- [ ] Notifications
- [ ] Mobile responsiveness
- [ ] Performance optimization

---

**Made with ❤️ for the community**
