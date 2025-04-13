smart-hotel-booking-system/
├── backend/
│   ├── SmartHotel.API/
│   │   ├── Controllers/
│   │   ├── Models/
│   │   ├── DTOs/
│   │   ├── Services/
│   │   ├── Repositories/
│   │   ├── Middleware/
│   │   ├── Program.cs
│   │   ├── appsettings.json
│   │   └── SmartHotel.API.csproj
│   └── SmartHotel.sln
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/         # API calls to backend
│   │   ├── context/          # Auth context / state
│   │   ├── routes/
│   │   ├── App.js / App.tsx
│   │   └── index.js / index.tsx
│   ├── package.json
│   └── vite.config.js / webpack.config.js
│
├── database/
│   ├── init.sql             # SQL scripts to create tables
│   └── seed.sql             # Sample data insert
│
├── README.md
└── .gitignore
