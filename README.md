# 🌱 Upcyclers Web Application - Capstone Project - Dicoding Study Independent Batch 7 

## 📖 About
Upcyclers is a web platform that connects waste collectors with individuals/businesses looking to sell recyclable materials. The application facilitates sustainable waste management by promoting reuse and recycling.

### ✨ Key Features
- 🔐 User authentication & profile management
- 📦 Buy & sell recyclable items
- 🗺️ Geolocation-based collector search
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
# clone reporistory backend
git clone https://github.com/Upcyclerscaps/Upcyclers-Backend

# clone reporistory frontend
git clone https://github.com/Upcyclerscaps/Upcyclers-Frontend
```
2. Install dependencies for frontend
```bash
cd Upcyclers-Frontend
npm install
```

3. Install dependencies for backend
```bash
cd Upcyclers-Backend
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
API_BASE_URL=ur_backend_url/api/v1
```

5. Run the application
```bash
# Run backend (from backend directory)
npm run dev
```

# Run frontend (from frontend directory)
```bash
# Run Tailwind
npx tailwindcss -i ./src/styles/input.css -o ./src/styles/style.css --watch

npm run build
npm run serve
```

📁 Project Structure
Frontend Structure
```bash
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
```
Backend Structure
```bash
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
```
🔑 API Documentation
Full API documentation is available at /api-docs when running the backend server.

https://upcyclers.servehttp.com/api-docs

🎯 Features In Detail
- Authentication & Authorizatio
- JWT-based authentication
- Role-based access control
- Secure password hashing with bcrypt

Geolocation Features
- location tracking
- Nearby seller/buyer search
- Address autocomplete

File Management
- Image upload with Cloudinary
- File type validation
- Image optimization

User Management
- Profile customization
- Location management
- Details Products

👥 Team CS7-F012
- ✨ [(F1567YB21) – (Dimas Julian) - ( Front-End Developer )](https://github.com/dims572)
- ✨ [(F1287YB32) – (Herdiansyah Ramadhana) - ( Back-End Developer )](https://github.com/Herazor)
- ✨ [(F0097YB63) – (Shahril Wahyu Nugroho) - ( Back-End Developer )](https://github.com/rlexs)
- ✨ [(F0097YB69) – (Zaidan Rivandani) - ( Front-End Developer )](https://github.com/zaidrvnd)

🙏 Acknowledgments
[Tailwind CSS](https://tailwindcss.com/docs/installation/using-postcss)
[Leaflet.js](https://leafletjs.com/examples/quick-start/)
[Cloudinary](https://cloudinary.com/documentation)
[MongoDB Atlas](https://www.mongodb.com/docs/atlas/)

