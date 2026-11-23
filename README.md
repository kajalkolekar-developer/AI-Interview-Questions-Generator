# AI-Interview-Questions-Generator
AI-powered interview question generator using React.js, Java, Spring Boot and Google Gemini API. Generate customized interview questions based on technology, topic, experience level, question type and question count.
# 🤖 AI Interview Questions Generator

## 📌 About the Project

AI Interview Questions Generator is an AI-powered web application designed to help students, freshers and experienced developers prepare for technical interviews.

Users can generate customized interview questions by selecting their preferred technology, entering a specific topic, choosing their experience level, selecting the question type and specifying the number of questions.

The application uses the **Google Gemini API** to generate interview questions based on user requirements. The frontend is developed using React.js, while the backend is built using Java and Spring Boot.

## ✨ Features

- **Technology Selection:** Choose from Java, Python, Spring Boot and React JS.
- **Topic-Based Questions:** Enter specific topics such as OOP, Arrays, Loops and more.
- **Experience Level:** Generate questions for Freshers, 1–2 years, 3–5 years and 5+ years.
- **Question Type:** Choose Subjective or Objective questions.
- **Question Count:** Generate 5, 10, 20, 30, 40 or 50 questions.
- **AI Integration:** Uses Google Gemini API for AI-powered question generation.
- **Dynamic Results:** Displays generated questions on the frontend.
- **REST API Integration:** React.js communicates with the Spring Boot backend using Axios.

## 🛠️ Technologies Used

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Bootstrap
- Bootstrap Icons
- Axios

### Backend
- Java
- Spring Boot
- Spring REST API
- RestTemplate

### Database
- MySQL

### AI Integration
- Google Gemini API

## ⚙️ How It Works

1. Select a technology such as Java, Python, Spring Boot or React JS.
2. Enter the topic for which you want interview questions.
3. Select your experience level.
4. Choose the question type (Subjective or Objective).
5. Select the number of questions.
6. Click on the **Generate Questions** button.
7. The React frontend sends the selected details to the Spring Boot backend using an HTTP POST request.
8. The backend communicates with the Google Gemini API to generate questions.
9. The generated questions are returned to the frontend and displayed to the user.

## 🔗 API Integration

**API Endpoint:**

`POST /sendRequest`

**Request Parameters:**

- technology
- topic
- experiencelevel
- questiontype
- questioncount

**Response:**

The backend returns the generated interview questions through the `generatedquestions` response field.

## 🎯 Project Objective

The main objective of this project is to make interview preparation easier through Artificial Intelligence. It provides customized interview questions according to the user's selected technology, topic and experience level.

It also demonstrates practical knowledge of full-stack web development, REST API integration and AI API communication.

## 👩‍💻 Developed By

**Kajal Dhulappa Kolekar**

Full Stack Technologies: Java | Spring Boot | React.js | MySQL | Google Gemini API

