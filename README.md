# 🏠 Property Listing System

A modern, secure, and feature-rich property listing platform built with Node.js, Express, and TypeScript.

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

## ✨ Features

- 🔐 Secure authentication and authorization
- 🏘️ Property listing management
- ❤️ Favorite properties system
- 🎯 Smart property recommendations
- 🛡️ Advanced security with Helmet
- 🔄 CORS protection
- 🧹 XSS protection with DOMPurify
- 📝 Input validation
- 🚀 High-performance API endpoints

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/property-listing-system.git
cd property-listing-system
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory:
```env
PORT=3000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CORS_ORIGIN=http://localhost:3000
```

4. Start the development server:
```bash
npm run dev
```

## 📚 API Documentation

### Authentication Endpoints
- `POST /api/v1/users/register` - Register a new user
- `POST /api/v1/users/login` - Login user
- `GET /api/v1/users/profile` - Get user profile

### Property Endpoints
- `GET /api/v1/properties` - Get all properties
- `POST /api/v1/properties` - Create new property
- `PATCH /api/v1/properties/update/:propertyId` - Update property
- `DELETE /api/v1/properties/delete/:propertyId` - Delete property

### Favorites Endpoints
- `GET /api/v1/favorites` - Get user's favorite properties
- `POST /api/v1/favorites/:propertyId` - Add property to favorites
- `DELETE /api/v1/favorites/:propertyId` - Remove property from favorites

### Recommendations Endpoints
- `GET /api/v1/recommendations` - Get personalized property recommendations

## 🛠️ Project Structure

```
src/
├── config/         # Configuration files
├── constants/      # Constant values
├── controllers/    # Route controllers
├── helpers/        # Helper functions
├── middlewares/    # Custom middlewares
├── models/         # Database models
├── routes/         # API routes
├── types/          # TypeScript types
├── utils/          # Utility functions
├── validations/    # Input validation schemas
└── server.ts       # Application entry point
```

## 🔒 Security Features

- JWT-based authentication
- Password hashing
- CORS protection
- Helmet security headers
- XSS protection
- Input sanitization
- Rate limiting
- Request validation

## 🧪 Testing

```bash
# Run tests
npm test

# Run tests with coverage
npm run test:coverage
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email support@yourdomain.com or create an issue in the repository.

---

Made with ❤️ by [Your Name] 