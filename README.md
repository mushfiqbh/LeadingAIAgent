# LeadingAI - AI-Powered Chat Platform for University Students

## Original repository is private.
## To collaborate, contact with me.

![LeadingAI-Chat-Page](https://drive.usercontent.google.com/download?id=1_2S_e2F3RS48RRiayEn2WypIQbewvzNA&export=download&authuser=0&confirm=t&uuid=c5dbad1f-e8a9-4cb4-ab0a-9aecad10db44&at=AN8xHoo4E_7Ksfvw687yvbqUYM24:1751736529896)

LeadingAI is a comprehensive AI-powered chat platform designed specifically for Leading University students. Built with Next.js, Express.js, and Firebase, it provides real-time AI assistance, academic resources, and collaborative features tailored to university life.

## 🚀 Key Features

### 💬 AI Chat Assistant
- Real-time chat with intelligent AI assistant
- Streaming responses for optimal user experience
- OpenAI-compatible message formatting
- Time-to-first-byte (TTFB) latency tracking
- Suggested prompts for quick interactions

### 👤 User Profile Management
- Complete student profile with automatic saving
- Birthdate field with intuitive date picker
- Real-time profile sync with status indicators
- Context-aware AI responses based on user profile

### � Academic Resources
- Class routine and exam schedule integration
- Bus schedule and notice board
- PDF note uploads and sharing
- Collaborative resource contribution system

### 🔐 Authentication & Security
- Firebase Authentication integration
- Email verification system
- Secure user session management
- Protected routes and API endpoints

### 📱 Modern UI/UX
- Responsive design with glassmorphism effects
- Gradient-based modern interface
- Dark/light theme support
- Intuitive navigation and user experience

## 🛠️ Technical Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first CSS framework
- **Firebase Client SDK** - Real-time database and authentication

### Backend
- **Express.js** - Node.js web framework
- **TypeScript** - Server-side type safety
- **Firebase Admin SDK** - Server-side Firebase operations
- **OpenAI API** - AI chat functionality
- **Cloudinary** - Image upload and management

### Database & Storage
- **Firestore** - NoSQL document database
- **Firebase Storage** - File storage solution
- **Cloudinary** - Image optimization and CDN

## 🎯 Core Functionalities

### Chat System
- Real-time message synchronization
- Image upload with background processing
- Message history persistence
- Error handling and recovery
- Typing indicators and status updates

### Profile Management
- Auto-save functionality with debounce
- Profile completion tracking
- Academic information integration
- Privacy-focused data handling

### Resource Sharing
- Google Sheets integration for schedules
- Multi-file PDF upload support
- Image upload for notices and announcements
- Community contribution tracking

### Analytics & Reporting
- Chat interaction analytics
- User engagement metrics
- Performance monitoring
- Error tracking and reporting

## 📊 Project Structure

```
LeadingAI/
├── client/                 # Next.js frontend application
│   ├── src/
│   │   ├── app/           # App Router pages
│   │   ├── components/    # Reusable UI components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility libraries
│   │   └── services/      # API services
│   └── public/            # Static assets
├── server/                # Express.js backend
│   └── src/
│       ├── controllers/   # Route handlers
│       ├── middlewares/   # Custom middleware
│       ├── routes/        # API routes
│       ├── services/      # Business logic
│       └── utils/         # Helper functions
└── docs/                  # Documentation files
```

## 📚 Documentation

- [Firebase Setup & Configuration](./FIREBASE_SETUP.md) - Complete Firebase integration guide
- [Architecture Overview](./ARCHITECTURE.md) - System design and component documentation
- [API Documentation](./API_DOCS.md) - Backend API reference
- [Troubleshooting Guide](./TROUBLESHOOTING.md) - Common issues and solutions

## 🎓 About LeadingAI

LeadingAI is designed to enhance the academic experience at Leading University by providing:
- Personalized AI assistance for academic queries
- Centralized access to university resources
- Collaborative platform for knowledge sharing
- Modern, intuitive interface for seamless interaction

The platform leverages cutting-edge AI technology to understand student needs and provide relevant, contextual assistance while maintaining data privacy and security standards.

---

*Empowering Leading University students with AI-driven academic assistance.*
