# Real-Time Pose Detection & AI Fitness App



## 📱 Project Overview

The **Real-Time Pose Detection App** is a Flutter-based fitness application that combines real-time exercise tracking with AI-powered fitness assistance. It helps users explore exercises, monitor their workout performance, and track basic fitness metrics through an interactive mobile experience.

The application uses **Google ML Kit Pose Detection** to analyze body landmarks and identify exercise movements. Each supported exercise has its own detection logic to count repetitions in real time and help users understand whether they are performing the movement correctly.

An integrated **Gemini AI chatbot** provides personalized exercise suggestions based on user-provided information, fitness goals, and the exercises available in the application.

**Platform:** Android  
**Framework:** Flutter  
**Language:** Dart  
**State Management:** GetX

<img width="403" height="865" alt="472408953-d9192de0-1c51-46ad-a895-5ca807f91d50" src="https://github.com/user-attachments/assets/1fb38ef4-3e26-4d07-b071-cc087b79472b" />
<img width="401" height="852" alt="472409192-49664109-1db9-430d-aee3-b0e4e02fe14c" src="https://github.com/user-attachments/assets/40a225f6-765b-40d7-b7e2-d256e30ee93c" />
<img width="400" height="858" alt="472409719-04570713-155a-44a6-abea-496868f991b7" src="https://github.com/user-attachments/assets/6e3ec30c-e0f0-4a37-bf78-a1991b0fb075" />
<img width="404" height="856" alt="472409353-1a579a1e-0cae-4044-b039-267fb02cb752" src="https://github.com/user-attachments/assets/59b32051-50bf-4d61-a043-789bb88de016" />
<img width="403" height="859" alt="472409805-e5452030-f0a4-4865-ae64-731696659cb2" src="https://github.com/user-attachments/assets/b88cbb59-2247-49ee-b4a8-d25e0415ea25" />
<img width="480" height="860" alt="472410271-666ab244-e1bd-48e5-a31a-8084143d3888" src="https://github.com/user-attachments/assets/df8b2851-fabb-449e-99dc-eb8c8b7219d0" />
<img width="481" height="862" alt="472410296-3e2a30ba-412a-4faa-94e9-fd377bc66e86" src="https://github.com/user-attachments/assets/bb581571-cb8a-4eda-b5ac-752c107442b6" />

<img width="398" height="854" alt="8" src="https://github.com/user-attachments/assets/f07be37e-9a67-4f95-8483-d6de11b4cedd" />
<img width="340" height="720" alt="9" src="https://github.com/user-attachments/assets/948a944c-a40f-4927-9199-fd72cef68fca" />
<img width="335" height="720" alt="10" src="https://github.com/user-attachments/assets/7c899094-6043-477f-8af3-e7da450e8903" />
<img width="340" height="720" alt="11" src="https://github.com/user-attachments/assets/b10c4040-c5ab-42d0-a903-16136438a28c" />
<img width="335" height="720" alt="12" src="https://github.com/user-attachments/assets/a76d1257-5cbf-4bc5-acd8-fd7b072f55fa" />


<img width="400" height="861" alt="472410719-685169a8-0f05-4319-aa8f-32a281c10341" src="https://github.com/user-attachments/assets/fb39dbe1-fc5b-482c-893e-9a1932144176" />

## 🎯 Project Objective

The objective of this project is to combine computer vision and generative AI to create an interactive fitness experience. By integrating real-time pose detection, exercise-specific repetition counting, AI-based exercise suggestions, and fitness progress tracking, the application helps users engage with workouts and monitor their fitness journey.

**Technologies:** Flutter · Dart · GetX · Google ML Kit · Gemini API · Firebase Authentication · Camera · BMI Calculation · Fitness Analytics


## ✨ Key Features

### 🔐 Authentication & User Profiles
- Splash screen and application entry flow.
- User registration and login using Firebase Authentication.
- User profile management.
- Access to authentication-dependent workout and pose detection features.

### 🏋️ Exercise Library
Browse available exercises and view their details before starting a workout.

Supported exercises include:
- Push-ups
- Squats
- Jumping Jacks
- Plank to Downward Dog
- Overhead Arm Clap

### 📸 Real-Time Pose Detection
- Integrate Google ML Kit for pose detection.
- Detect body landmarks through the device camera.
- Implement exercise-specific movement detection algorithms.
- Count repetitions in real time based on detected movements.
- Provide movement feedback to help users assess exercise form.

### 🤖 AI-Powered Fitness Assistant
- Integrate the Gemini API for conversational fitness assistance.
- Collect relevant user information, such as name, age, height, weight, and gender.
- Understand fitness goals, such as weight loss or weight gain.
- Generate exercise suggestions based on the user's stated goals and the exercises available in the application.
- Allow users to interact with the AI assistant through a chat interface.

*AI-generated recommendations are informational and should not replace advice from a qualified fitness or healthcare professional.*

### 📊 Fitness Dashboard & BMI Calculator
- Calculate Body Mass Index (BMI) using height and weight.
- Display BMI results for basic fitness awareness.
- Present fitness progress through graphs.
- Help users review recorded fitness metrics over time.

### 🔓 Guest & Authenticated Experience
- Allow users to explore available exercises and access the BMI calculator without signing in, where supported.
- Require authentication for pose detection and other protected functionality.
- Provide a more personalized experience for authenticated users.

## 🔄 Application Flow

1. **Launch the app** – Display the splash screen and initialize the application.
2. **Explore the application** – Browse available exercises and access the BMI calculator.
3. **Sign up or log in** – Authenticate through Firebase to access protected features.
4. **Set fitness goals** – Provide relevant profile information and fitness objectives to the AI assistant.
5. **Get exercise suggestions** – Receive Gemini-generated recommendations from the available exercise library.
6. **Select an exercise** – Open the exercise details and start the workout.
7. **Enable pose detection** – Use the camera and Google ML Kit to detect body landmarks.
8. **Track repetitions** – Apply exercise-specific detection logic to count movements in real time.
9. **Review fitness progress** – Check BMI results and view available progress graphs.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Flutter | Cross-platform mobile application development |
| Dart | Application programming language |
| GetX | State management and application navigation |
| Google ML Kit Pose Detection | Real-time body landmark detection |
| Gemini API | AI-powered fitness chatbot and exercise suggestions |
| Firebase Core | Firebase initialization |
| Firebase Authentication | User registration and login |
| Camera | Camera access for pose detection |
| Charts / Graph Components | Fitness progress visualization |

## 👨‍💻 Development Contributions

- Developed a Flutter-based fitness application with exercise browsing, workout tracking, and user profile functionality.
- Integrated Firebase Authentication for user registration and login.
- Implemented real-time pose detection using Google ML Kit.
- Developed exercise-specific movement detection algorithms to identify repetitions and track workout activity.
- Integrated the Gemini API to provide conversational fitness assistance and goal-based exercise suggestions.
- Implemented a BMI calculator using user height and weight.
- Developed fitness dashboard components and progress graphs.
- Used GetX for state management and application navigation.
- Implemented access restrictions for authentication-dependent workout functionality.



