
# 🍔 FoodieApp

FoodieApp is a modern food-exploration and review web application. It allows users to discover restaurants, browse dishes, post reviews, and interact with food content shared by others. The goal of the project is to create a smooth, social, and fun experience for food lovers.

## 📌 Table of Contents
- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🧾 About
FoodieApp is built to help users explore new restaurants and dishes, share experiences through ratings and reviews, and follow other foodies’ recommendations.

## ⭐ Features
- Register/Login
- Explore restaurants, meals, cuisines
- View details, reviews, ratings
- Submit reviews and upload images
- Search & filter restaurants
- Responsive design

## 🛠 Tech Stack
- ASP.NET / ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server
- Optional frontend (Angular/React)

## 🚀 Getting Started

### ✔ Prerequisites
- .NET SDK
- SQL Server
- Git

### 📥 Installation
```bash
git clone https://github.com/Arsany-Naim/FoodieApp.git
cd FoodieApp/Foodie_Web_API
dotnet restore
```

Configure DB in `appsettings.json`:
```json
"ConnectionStrings": {
  "DefaultConnection": "YOUR_DB_CONNECTION_STRING"
}
```

## ▶ Running the Application
```bash
dotnet build
dotnet run
```

## 🧪 Usage
Use Swagger/Postman/frontend to interact with:
- /api/Restaurants
- /api/Reviews
- /api/Auth
- /api/Users

## 📁 Project Structure
```
FoodieApp/
├── Foodie_Web_API/
│   ├── Controllers/
│   ├── Models/
│   ├── Data/
│   ├── appsettings.json
│   └── Foodie_Web_API.sln
└── README.md
```

## 🤝 Contributing
1. Fork repo  
2. Create branch  
3. Commit & push  
4. Open PR  

## 📜 License
MIT License

## 📬 Contact
Author: Arsany Naim  
GitHub: https://github.com/Arsany-Naim  
Repo: https://github.com/Arsany-Naim/FoodieApp
