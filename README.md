# HealthSchedulePro

HealthSchedulePro is a comprehensive healthcare management system that connects patients with healthcare providers, enabling seamless appointment scheduling, medical record management, and healthcare service delivery.

## 🚀 Features

- **User Authentication**
  - Secure login and registration for patients and doctors
  - Role-based access control
  - Protected routes and sessions

- **Appointment Management**
  - Schedule, reschedule, and cancel appointments
  - Real-time availability checking
  - Appointment reminders and notifications
  - View appointment history

- **Medical Records**
  - Digital medical record management
  - Secure storage and access
  - Patient history tracking
  - Prescription management

- **Doctor Dashboard**
  - Patient management
  - Appointment calendar
  - Medical record creation and management
  - Analytics and reporting

- **Patient Dashboard**
  - View and book appointments
  - Access medical records
  - View prescriptions
  - Track healthcare history

## 🛠️ Technologies Used

### Frontend
- **React** - UI library
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Component library
- **React Query** - Data fetching and caching
- **React Router** - Client-side routing
- **Lucide Icons** - Icon library

### Backend
- **Firebase**
  - Authentication
  - Firestore Database
  - Cloud Functions
  - Storage

### Development Tools
- **Vite** - Build tool and development server
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Git** - Version control

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v16 or higher)
- npm or yarn
- Git

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/HealthSchedulePro.git
   cd HealthSchedulePro
   ```

2. **Install dependencies**
   ```bash
   # Install client dependencies
   cd client
   npm install

   # Install server dependencies
   cd ../server
   npm install
   ```

3. **Environment Setup**

   Create a `.env` file in the client directory:
   ```env
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   ```

4. **Start the development server**
   ```bash
   # Start client
   cd client
   npm run dev

   # Start server (in a new terminal)
   cd server
   npm run dev
   ```

5. **Access the application**
   - Client: http://localhost:5173
   - Server: http://localhost:5000

## 📁 Project Structure

```
HealthSchedulePro/
├── client/                 # Frontend application
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── pages/        # Page components
│   │   ├── services/     # API services
│   │   ├── hooks/        # Custom hooks
│   │   ├── types/        # TypeScript types
│   │   └── utils/        # Utility functions
│   └── public/           # Static assets
│
└── server/                # Backend application
    ├── src/
    │   ├── controllers/  # Route controllers
    │   ├── models/       # Database models
    │   ├── routes/       # API routes
    │   └── utils/        # Utility functions
    └── config/           # Configuration files
```

## 🔐 Authentication

The application uses Firebase Authentication with the following features:
- Email/Password authentication
- Role-based access (Patient/Doctor)
- Protected routes
- Session management

## 📊 Database Schema

### Collections
- users
- appointments
- medicalRecords
- prescriptions
- notifications

## 🧪 Testing

```bash
# Run client tests
cd client
npm test

# Run server tests
cd server
npm test
```

## 📝 API Documentation

### Authentication Endpoints
- POST /api/auth/register
- POST /api/auth/login
- POST /api/auth/logout

### Appointment Endpoints
- GET /api/appointments
- POST /api/appointments
- PUT /api/appointments/:id
- DELETE /api/appointments/:id

### Medical Records Endpoints
- GET /api/medical-records
- POST /api/medical-records
- GET /api/medical-records/:id
- PUT /api/medical-records/:id

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Author

- EPU FAVOUR JESICA 

## 🙏 Acknowledgments

- Firebase for backend services
- Shadcn/ui for the component library
- All contributors who have helped shape this project

## 📞 Support

For support, email favourepu70@gmail.com or create an issue in the repository.
