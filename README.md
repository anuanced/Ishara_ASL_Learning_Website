## Abstract

ISHARA is a web-based learning platform developed to support beginners in understanding and practicing **American Sign Language (ASL)**. The project aims to promote inclusive communication by providing a visually driven and accessible interface for learning commonly used signs. By integrating multimedia resources such as images and videos, ISHARA focuses on improving conceptual clarity and retention for users with no prior exposure to sign language.

## 1. Introduction

Sign language plays a critical role in enabling communication for individuals who are deaf or hard of hearing. However, access to structured and beginner-friendly learning resources remains limited, especially for informal learners. The ISHARA project addresses this gap by offering a browser-based learning environment that introduces users to ASL through visual demonstrations and simple navigation.

The project is designed as an educational web application and serves as an academic exploration of accessibility-oriented web development.

## 2. Objectives

The primary objectives of the ISHARA project are:

* To provide an introductory learning platform for American Sign Language
* To support visual learning through images and video-based demonstrations
* To design an accessible and intuitive user interface
* To encourage awareness of inclusive communication technologies

## 3. System Overview

ISHARA is implemented as a frontend-focused web application. The system presents sign language content using static assets such as images and videos, organized in a way that allows learners to easily associate gestures with meanings.

The application runs entirely in the browser and does not require backend services, making it lightweight and easy to deploy.

## 4. Technologies Used

* **HTML** – Structure of the web pages
* **CSS** – Styling and layout design
* **JavaScript** – Client-side logic and interaction handling
* **Vite** – Development server and build optimization
* **ESLint** – Code quality and consistency enforcement

## 5. Project Structure

```
ISHARA/
│── index.html
│── index.js
│── package.json
│── vite.config.js
│── eslint.config.js
│
├── assets/
│   ├── ASL alphabet images
│   ├── Gesture reference images
│   ├── Video demonstrations (MP4 format)
│
└── README.md
```

## 6. Installation and Execution

To run the project locally, the following steps should be followed:

### Step 1: Clone the Repository

```bash
git clone https://github.com/anuanced/Ishara_ASL_Learning_Website.git
cd Ishara
```

### Step 2: Install Dependencies

```bash
npm install
```

### Step 3: Start the Development Server

```bash
npm run dev
```

The application will be accessible at:

```
http://localhost:5173/
```

## 7. Use Case Description

The platform is intended for:

* Students seeking an introduction to sign language
* Individuals interested in accessibility and inclusive communication
* Educational demonstrations of multimedia-based learning systems

Users interact with visual representations of signs, enabling learning through observation and repetition.

## 8. Limitations

* The current version does not support real-time gesture recognition
* No user authentication or progress tracking is implemented
* The application focuses only on introductory ASL content

These limitations were accepted to maintain simplicity and focus on core learning objectives.

## 9. Future Scope

Possible enhancements to the system include:

* Integration of AI-based hand gesture recognition
* Addition of quizzes and learning progress tracking
* Support for multiple sign languages
* Improved responsiveness for mobile devices

## 10. Conclusion

ISHARA demonstrates how web technologies can be effectively used to develop accessible educational tools. The project highlights the importance of inclusive design and serves as a foundation for more advanced sign language learning systems incorporating intelligent recognition and adaptive learning features.
