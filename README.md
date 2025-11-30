# 🚀 Pult Store 2.0


## 🛒 Современный интернет-магазин с полной авторизацией, корзиной и админ-панелью


## ✨ Возможности
### 🔐 Полная авторизация: Регистрация, вход, OTP-подтверждение email

### 🛒 Корзина и заказы: Добавление/удаление товаров, оформление

### 📱 Адаптивный дизайн: Mobile-first подход

### 👨‍💼 Админ-панель: Управление товарами и заказами

### 📧 Email-уведомления: Подтверждение аккаунта и заказов

### 🚀 Быстрый запуск: Backend + Frontend в одном репо

## 🛠 Технологии
#### Frontend	Backend	База данных	Инструменты
#### React 18	Express.js	MongoDB	Vite
#### React Router	Node.js	Mongoose	Axios
#### Tailwind CSS	JWT Auth		React Toastify
#### React Context	Nodemailer

## ⚙️ Быстрый запуск

### 🔧 Предварительные требования
#### Node.js 18+ | MongoDB Atlas | Git
### 1. Клонируйте репозиторий
#### git clone https://github.com/artEvg/pult-store-2.0.git
#### cd pult-store-2.0
### 2. Backend (server)
#### cd server
#### cd .env.example .env
### Настройте .env (JWT_SECRET, MONGO_URI, EMAIL)
#### npm install
#### npm run server
#### Backend: http://localhost:4000

### 3. Frontend (client)
#### cd ../client
#### npm install
#### npm run dev
#### Frontend: http://localhost:5173

## 📁 Структура проекта
#### pult-store-2.0/
#### ├── client/                 # React + Vite + Tailwind
#### │   ├── src/
#### │   │   ├── components/     # Navbar, ProtectedRoute
#### │   │   ├── pages/          # Login, EmailVerify, AdminDashboard
#### │   │   └── context/        # AppContext (auth, cart)
#### ├── server/                 # Express + MongoDB
#### │   ├── controllers/        # authControllers.js (OTP!)
#### │   ├── models/             # User.js, Product.js
#### │   ├── routes/             # authRoutes.js
#### │   └── middleware/         # userAuth.js (JWT)
#### └── README.md

## 🎮 Демо-тест
### 1️⃣ /register → test@example.com
### 2️⃣ /login → Cookie токен
### 3️⃣ Navbar → "Подтвердить" → OTP на почту
### 4️⃣ /email-verify → Введите код ✅
### 5️⃣ /admin → Панель администратора

## 🔍 API Endpoints
#### Метод	Endpoint	Описание	Auth
#### POST	/api/auth/register	Регистрация	Нет
#### POST	/api/auth/login	Вход	Нет
#### POST	/api/auth/send-verify-otp	Отправить OTP	Да
#### POST	/api/auth/verify-account	Подтвердить email	Нет
#### GET	/api/user/data	Данные профиля	Да

## 🤝 Как внести вклад

#### Форкните репозиторий
#### Создайте ветку git checkout -b feature/amazing-feature
#### Зафиксируйте изменения git commit -m 'Add amazing feature'
#### Отправьте в ветку git push origin feature/amazing-feature
#### Откройте Pull Request

## 📄 Лицензия

MIT - используйте на здоровье! 🚀

### 👤 Автор: artEvg
### ⭐ Звезду репозиторий, если помог!

## Скопируйте в README.md и сделайте:
### git add README.md
### git commit -m "✨ Add beautiful README with badges & demo"
### git push origin main
