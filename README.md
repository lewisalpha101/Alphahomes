smart-homes-booking/
├── backend/                 # Node.js + Express Backend
│   ├── controllers/
│   │   ├── authController.js    # Login/Register logic
│   │   ├── bookingController.js # Booking management
│   │   └── deviceController.js  # MQTT device commands
│   ├── models/
│   │   ├── User.js              # Mongoose schema
│   │   ├── Property.js
│   │   └── Booking.js
│   ├── routes/
│   │   ├── authRoutes.js        # /api/auth
│   │   ├── bookingRoutes.js     # /api/bookings
│   │   └── deviceRoutes.js      # /api/devices
│   ├── services/
│   │   ├── mqttService.js       # MQTT connect & publish
│   │   └── authService.js       # JWT handling
│   ├── middleware/
│   │   └── authMiddleware.js    # Protect routes
│   ├── config/
│   │   ├── db.js                # MongoDB connection
│   │   └── mqtt.js              # MQTT broker config
│   └── index.js                 # Express server
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   └── Navbar.jsx
│   │   ├── pages/
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Properties.jsx
│   │   │   └── Bookings.jsx
│   │   ├── services/
│   │   │   └── api.js           # Axios config
│   │   ├── context/
│   │   │   └── AuthContext.js
│   │   └── App.jsx
│   └── tailwind.config.js
│
├── mobile-app/
│   ├── lib/
│   │   ├── screens/
│   │   │   ├── HomeScreen.dart
│   │   │   ├── BookingScreen.dart
│   │   │   └── ProfileScreen.dart
│   │   ├── models/
│   │   │   └── Property.dart
│   │   ├── services/
│   │   │   ├── ApiService.dart
│   │   │   └── MqttService.dart
│   │   └── main.dart
│   └── pubspec.yaml
│
├── iot-device-control/
│   ├── mqtt-client/
│   │   └── connect.js           # Sub/Pub test to MQTT broker
│   ├── firmware/
│   │   └── esp32-lock.ino       # Smart lock firmware
│   └── README.md
│
├── database/
│   ├── schema.sql
│   ├── seed.js
│   └── firebase.rules
│
├── deployment/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   └── nginx/
│       └── default.conf
│
├── docs/
│   ├── API.md
│   ├── SYSTEM.md
│   ├── SETUP.md
│   └── FLOWCHARTS/
│
└── README.md
# Alphahomes
