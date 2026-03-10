# 🐾 CocoPaws Stray Care

A community-driven platform designed to support stray animals through adoption, feeding coordination, and volunteer initiatives.

---

## 📌 Problem

Many stray animals lack proper care, food, and adoption opportunities.  
Although many people are willing to help, there is no centralized platform that connects volunteers, feeders, adopters, and donors to coordinate efforts for stray animal welfare.

---

## 💡 Solution

CocoPaws Stray Care aims to bridge this gap by providing a community platform where users can contribute to the well-being of stray animals.

Through this platform, users and volunteers can:

- Report stray animals and update their last known location
- Post animals available for adoption
- Add and manage feeding spots for stray animals
- Coordinate volunteer activities
- Support feeding and medical care through donations

The goal is to make it easier for communities to collectively care for stray animals and improve their chances of receiving food, shelter, treatment, and adoption.

---

## ✨ Features

### Core Features
- User authentication (Signup/Login)
- Stray animal listing
- Adoption request system
- Volunteer registration
- Admin moderation

### Advanced Features
- Community feeding spot mapping
- Image upload for animal profiles
- Donation integration for feeding and treatment

---

## 🛠 Tech Stack

### Frontend
- React
- TypeScript
- Material UI

### Backend
- Spring Boot
- REST APIs
- JWT Authentication

### Database
- PostgreSQL

### Integrations
- Map integration for feeding spots
- Razorpay (for donation support)

---

## 🏗 System Architecture

The application follows a client-server architecture:

User → React Frontend → REST APIs → Spring Boot Backend → PostgreSQL Database

The frontend handles the user interface, the backend manages business logic and APIs, and the database stores user data, animal listings, and feeding information.

---

## 📁 Project Structure

cocopaws-stray-care
│
├── frontend/ # React + TypeScript application
├── backend/ # Spring Boot REST APIs
└── README.md

---

## 🚀 Setup Instructions

### 1. Clone the repository

git clone https://github.com/your-username/cocopaws-stray-care.git


### 2. Run Backend

- Navigate to the `backend` folder
- Start the Spring Boot application

### 3. Run Frontend

- Navigate to the `frontend` folder
- Install dependencies

npm install


- Start development server


npm start


Open the application in your browser.

---

## 🔮 Future Enhancements

- Vet clinic directory
- Email notifications for adoption requests
- Analytics dashboard for animal welfare insights
- Mobile application support

---

## ❤️ Inspiration

This project was inspired by my dog **Coco**.

Before Coco came into my life, I always loved seeing dogs and puppies on the street, but I never truly understood their daily struggles. When Coco became a part of my life, I realized how animals communicate even without words — their need for food, care, safety, and love.  

CocoPaws Stray Care was created to make it easier for people to support stray animals through feeding, adoption, volunteering, and community coordination — helping them live happier, safer lives, just like Coco does.