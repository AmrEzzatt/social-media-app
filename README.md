🚀 Social Media App – Real-Time Chat Platform

Project Overview:
Developed a scalable social media application with real-time chat, advanced authentication, and privacy-focused features, designed for high performance and user engagement.

Tech Stack:

Backend: Node.js + Express (event-driven, scalable architecture)
Database: MongoDB + Mongoose (efficient data modeling)
Authentication & Security: JWT, bcrypt, OTP, crypto-js, CORS, Helmet, Rate Limiting
Real-Time Communication: Socket.io
APIs: GraphQL (flexible, granular queries) + REST (specific resource access)
File Handling: Multer + Cloudinary for seamless media uploads
Validation: Joi

Key Features:

Multi-Auth System: Email, Phone, and Google OAuth login/registration
Privacy-Controlled Posts: Users manage visibility (Public, Friends, or Selected Users)
Profile Views Tracking: Notifications when profiles are viewed 5+ times
Media Uploads: Smooth integration with Cloudinary
Soft Deletion & Archiving: Undo posts and auto-clean related comments/replies
Admin Role Management: Advanced user privileges and moderation
Real-Time Chat: Instant messaging with stable WebSocket connections
GraphQL-Powered Post Retrieval: Reduces over-fetching, improves performance
REST APIs: Complementary endpoints for resources like profiles and media

Challenges Solved:

Maintained stable WebSocket connections under high load for real-time chat
Efficiently managed multiple concurrent users with combined GraphQL + REST APIs
Optimized low-latency real-time messaging for a smooth user experience

Key Learnings:

Implementing WebSockets (Socket.io) for real-time applications
Designing a Node.js backend combining GraphQL and REST for efficiency
Applying performance optimization techniques in high-frequency real-time systems
