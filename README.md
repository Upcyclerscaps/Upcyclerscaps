- 👋 Ini Adalah Akun Github Project Capstone Dicoding STUPEN BATCH 7 2024
- 👀 ANGGOTA :
- ✨ (F1567YB21) – (Dimas Julian) - ( Front-End Developer )
- ✨ (F1287YB32) – (Herdiansyah Ramadhana) - ( Back-End Developer )
- ✨ (F0097YB63) – (Shahril Wahyu Nugroho) - ( Back-End Developer )
- ✨ (F0097YB69) – (Zaidan Rivandani) - ( Front-End Developer )

# 🌱 Upcyclers Web Application

<p align="center">
 <img src="public/images/logo.png" alt="Upcyclers Logo" width="200"/>
</p>

## 📖 About
Upcyclers is a web platform that connects waste collectors with individuals/businesses looking to sell recyclable materials. The application facilitates sustainable waste management by promoting reuse and recycling.

### ✨ Key Features
- 🔐 User authentication & profile management
- 📦 Buy & sell recyclable items
- 🗺️ Geolocation-based collector search
- 💬 Real-time chat between buyers & sellers
- 📱 Responsive design for all devices

## 🛠️ Tech Stack
- Frontend:
 - Vanilla JavaScript
 - Tailwind CSS
 - Webpack
 - Leaflet.js for maps
 
- Backend:
 - Node.js
 - Express.js
 - MongoDB
 - JWT Authentication
 
- Cloud Services:
 - MongoDB Atlas
 - Cloudinary (Image Storage)

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- NPM/Yarn

### Installation

1. Clone the repositor
```bash
git clone https://github.com/yourusername/upcyclers.git
cd upcyclers
```
2. Install dependencies for frontend
```bash
cd frontend
npm install
```

3. Install dependencies for backend
```bash
bashCopycd backend
npm install
```

4.Set up environment variables

# Backend .env
```bash
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

# Frontend config.js
```bash
API_BASE_URL=http://localhost:5000/api/v1
```
5. Run the application
```bash
bashCopy# Run backend (from backend directory)
npm run dev
```

# Run frontend (from frontend directory)
```bash
npm run start-dev
```

📁 Project Structure
Frontend Structure
frontend/
├── src/
│   ├── public/
│   ├── scripts/
│   │   ├── globals/
│   │   ├── services/
│   │   ├── routes/
│   │   └── views/
│   ├── styles/
│   └── templates/
└── webpack.config.js

Backend Structure
backend/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── utils/
└── app.js

🔑 API Documentation
Full API documentation is available at /api-docs when running the backend server.
https://upcyclers.servehttp.com/api-docs

🎯 Features In Detail
Authentication & Authorization

JWT-based authentication
Role-based access control
Secure password hashing with bcrypt

Geolocation Features
location tracking
Nearby seller/buyer search
Address autocomplete

File Management
Image upload with Cloudinary
File type validation
Image optimization

User Management

Profile customization
Location management
Details Products

📝 License
This project is licensed under the MIT License - see the LICENSE.md file for details
👥 Team

Frontend Developer - [Your Name]
Backend Developer - [Your Name]
UI/UX Designer - [Your Name]

🙏 Acknowledgments

Tailwind CSS
Leaflet.js
Cloudinary
MongoDB Atlas

📞 Contact
Your Name - @yourusername
