

# 🌐 Airbnb Clone

This project is a **full-stack Airbnb Clone** that replicates core functionalities of the Airbnb platform.  
It allows users to browse listings, book stays, and hosts to manage properties.  

---

## ✨ Features

### 🔑 Authentication & Authorization
- User signup/login with JWT & bcrypt
- Role-based access (Host / Guest)
- Secure cookies for session management

### 🏡 Listings
- Create, read, update, delete (CRUD) property listings
- Upload multiple images
- Filter listings by city, category, price, and availability

### 📅 Booking System
- Guests can book available listings
- Hosts can manage reservations
- Real-time availability updates

### 🌦️ Additional
- Integrated with weather & location APIs (future scope)
- Responsive UI with TailwindCSS

---

## 🛠️ Tech Stack

**Frontend**
- React + Vite  
- Tailwind CSS  
- Axios  

**Backend**
- Node.js + Express.js  
- MongoDB with Mongoose  

**Other Tools**
- JWT (authentication)  
- Cloudinary (image upload)  
- Git & GitHub (version control)  

---

## 📂 Folder Structure

```

Airbnb-/
│── backend/
│   ├── config/          # DB connection & environment configs
│   ├── controllers/     # Request handlers
│   ├── models/          # Mongoose schemas
│   ├── routes/          # API routes
│   └── server.js        # Entry point

│── frontend/
│   ├── public/          # Static files
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/       # React pages
│   │   ├── hooks/       # Custom hooks
│   │   └── App.js

│── .env                 # Environment variables (not pushed)
│── .gitignore
│── README.md

````

---

## 🚀 Getting Started

### 🔧 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/abhay34-ai/Airbnb-.git
   cd Airbnb-
````

2. Install backend dependencies:

   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:

   ```bash
   cd ../frontend
   npm install
   ```

---

### ▶️ Run Locally

Start **backend**:

```bash
cd backend
npm run dev
```

Start **frontend**:

```bash
cd frontend
npm run dev
```

---

## 🌐 API Endpoints

### Auth Routes

* `POST /api/auth/register` – Create new account
* `POST /api/auth/login` – Login user

### Listing Routes

* `GET /api/listings` – Get all listings
* `POST /api/listings` – Create a new listing (Host only)
* `PUT /api/listings/:id` – Update listing
* `DELETE /api/listings/:id` – Delete listing

### Booking Routes

* `POST /api/bookings` – Book a property
* `GET /api/bookings` – Get user bookings

---




## 🚧 Future Improvements

* Payment gateway integration (Stripe/PayPal)
* Reviews & Ratings system
* Maps integration (Google Maps API)
* Admin dashboard for site management

---

## 👤 Author & Contact

* **Name:** Abhay Thakre
* **Portfolio:** [abhay-portfolio-34.vercel.app](https://abhay-portfolio-34.vercel.app/)
* **LinkedIn:** [linkedin.com/in/abhay-thakre-a402b1370](https://www.linkedin.com/in/abhay-thakre-a402b1370/)
* **Email:** [thakreabhay450@gmail.com](mailto:thakreabhay450@gmail.com)


