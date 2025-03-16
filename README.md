# 🎬 Movie Showcase & Review App

A full-stack web application built with **React** for the frontend and **Spring Boot** for the backend. This website allows users to browse movies, watch trailers, and leave reviews.

---

## 🚀 Features

- 🎥 Browse movies with posters & details
- 📺 Watch trailers redirected to YouTube
- ✍️ Leave reviews for movies
- 🗄️ Backend powered by **Spring Boot** and **MongoDB**
- 🌐 Frontend built with **React** and **Bootstrap**

---

## 🛠️ Tech Stack

### Frontend
- **React.js** (with React Router)
- **Bootstrap** for UI styling
- **Axios** for API calls

### Backend
- **Spring Boot** (REST API)
- **Spring Data MongoDB** (MongoDB Database)
- **Lombok** to reduce boilerplate code

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/tashrif-007/MoviesSpringboot.git
cd MovieASpringboot  
```

### 2️⃣ Backend Setup (Spring Boot)
#### Prerequisites:
- Java 17+
- Maven
- MongoDB

#### Steps:
1. Configure MongoDB in `application.properties` (or `application.yml`):
   ```properties
   spring.data.mongodb.uri=mongodb://localhost:27017/movies-api-db
   ```
2. Navigate to the backend folder:
   ```sh
   cd MovieApi-backend
   ```
3. Build and run the Spring Boot application:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```
4. The backend will be available at `http://localhost:8080`

### 3️⃣ Frontend Setup (React)
#### Prerequisites:
- Node.js & npm

#### Steps:
1. Navigate to the frontend folder:
   ```sh
   cd movie-client
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```
4. The frontend will be available at `http://localhost:3000`

---

## 🔄 API Endpoints

### Movie Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| `GET`  | `/api/v1/movies` | Get all movies |
| `GET`  | `/api/v1/movies/{id}` | Get movie details |
| `POST` | `/api/v1/reviews` | Add a review |

---
## This project was only built for learning springboot and contains minimalistic features.
