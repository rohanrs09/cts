# 📁 Smart Hotel Booking System – Folder Structure

```text
smart-hotel-booking-system/
│
├── backend/                             → Backend (.NET Core Web API)
│   ├── SmartHotel.API/
│   │   ├── Controllers/                 → API route handlers (User, Hotel, Booking)
│   │   ├── Models/                      → Entity classes (User, Room, etc.)
│   │   ├── DTOs/                        → Data Transfer Objects for APIs
│   │   ├── Services/                    → Business logic (BookingService, etc.)
│   │   ├── Repositories/                → Database operations (EF Core)
│   │   ├── Middleware/                  → JWT, exception handlers, logging
│   │   ├── Program.cs                   → Entry point (config, middleware)
│   │   ├── appsettings.json             → DB connections, JWT secret, etc.
│   │   └── SmartHotel.API.csproj        → .NET project file
│   └── SmartHotel.sln                   → Solution file for backend
│
├── frontend/                            → Frontend (React + Vite/Webpack)
│   ├── public/                          → Static files (index.html, favicon)
│   ├── src/
│   │   ├── assets/                      → Images, icons, fonts
│   │   ├── components/                  → Reusable UI components
│   │   ├── pages/                       → Route-level pages (Home, Login, etc.)
│   │   ├── services/                    → Axios calls to backend APIs
│   │   ├── context/                     → Auth/user context
│   │   ├── routes/                      → React Router config
│   │   ├── App.js / App.tsx            → Main React app file
│   │   └── index.js / index.tsx        → React entry point
│   ├── package.json                     → NPM dependencies
│   └── vite.config.js / webpack.config.js → Vite/Webpack build config
│
├── database/                            → SQL scripts for DB
│   ├── init.sql                         → Table creation script
│   └── seed.sql                         → Sample hotel, room, booking data
│
├── README.md                            → Project overview, setup instructions
└── .gitignore                           → Files/folders to ignore in Git
