
# BODYCRAFT

## DEVELOPERS

- Abinash Giri
- Aditya Raj
- Kumar Ravi
- Jay Gupta

**Content of Read Md file:**
- Introduction & Features
- Tech Stack
- Setup Instructions for Bodycraft
- Dependancies
- Abstract

Demo: 
<a href="https://body-craft.vercel.app/"> Check Out<a/>

**1.Introduction & Features**
Bodycraft is an advanced AI-powered fitness tracker designed to help users monitor their workouts and yoga poses in real-time. It provides personalized fitness guidance by calculating BMI (Body Mass Index) and suggesting diet plans and exercises accordingly.
Key Features
1.BMI Calculation & Fitness Suggestions:
o	Users can input their height and weight to determine their BMI.
o	Based on BMI, the system suggests personalized diets and exercises to achieve fitness goals.

**2.Exercise Progress Tracking:**
o	Real-time tracking of the following exercises using MediaPipe:
	Bicep Curls
	Push-ups
	Squats
	Crunches
o	The system counts reps and ensures correct posture for optimal results.

**3.Yoga Pose Recognition:**
o	Supports real-time posture correction and tracking for:
	Trikonasana (Triangle Pose)
	Virabhadrasana (Warrior Pose)
	Adho Mukha Svanasana (Downward Dog Pose)
o	Helps users maintain proper form and alignment during yoga practice.

**4.Technologies Used:**
•	HTML, CSS, React – Frontend for an interactive user experience.
•	MediaPipe – AI-powered motion tracking for exercise and yoga pose detection.
•	Firebase – Backend for real-time data storage and user authentication.

**5.Setup Instructions for Bodycraft :**
Prerequisites 
Ensure you have the following installed before setting up the project: 
• Node.js (LTS version) – Download 
• npm (comes with Node.js) or yarn (optional) 
• Firebase Account – Sign up 

1. Clone the Repository 
git clone https://github.com/your-username/bodycraft.git 
cd bodycraft

3. Install Dependencies 
Run the following command to install the required packages: 
npm install  # or yarn install

5. Set Up Firebase
6.   1. Create a Firebase project at Firebase Console. 
     2. Enable Authentication (Google or Email/Password). 
     3. Set up Firestore Database. 
     4. Get your Firebase config and create a .env file in the project root: 
     5. REACT_APP_API_KEY=your_api_key 
     6. REACT_APP_AUTH_DOMAIN=your_auth_domain 
     7. REACT_APP_PROJECT_ID=your_project_id 
     8. REACT_APP_STORAGE_BUCKET=your_storage_bucket 
     9. REACT_APP_MESSAGING_SENDER_ID=your_sender_id 
        REACT_APP_APP_ID=your_app_id
        
4. Run the Development Server 
Start the React development server: 
npm start  # or yarn start 
The app should now be running at http://localhost:3000/.

6. Deploying the Project 
To deploy using Firebase Hosting: 
npm run build  # Build the project 
firebase init  # Initialize Firebase (choose Hosting) 
firebase deploy  # Deploy to Firebase

8. Additional Notes 
• Ensure you have a webcam connected for MediaPipe to track movements. 
• If tracking is inaccurate, adjust MediaPipe model parameters in the code. 
• Contributions are welcome! Feel free to open an issue or pull request.

Tech Stack 
• React.js – Frontend framework 
• MediaPipe – AI-powered motion tracking 
• Firebase – Authentication & database 
• HTML, CSS – UI design

**8.Abstract:**
Utilization of Augmented Reality (AR) technology to create an engaging and interactive experience.
Offering a variety of workout programs tailored to diverse fitness goals and levels.
Monitoring progress and maintaining a history of workouts.
Providing personalized feedback and guidance to enhance technique and performance.
Progressive Web App (PWA) designed for optimal viewing across multiple devices.
##Front-End
We are using React, a widely-used front-end framework, to develop our user interface in a modular and scalable manner. Its component-based architecture simplifies the management of various UI elements, and the virtual DOM enhances the performance of our application.
Material UI is a renowned React component library that offers pre-built, customizable UI components adhering to Google's Material Design principles. These components facilitate the creation of visually appealing and responsive user interfaces effortlessly.
##Back-End
##Firebase:
Firebase is a cloud-based platform that offers a variety of services and tools for developing and managing web and mobile applications. Key features of Firebase include:

Realtime Database: A NoSQL database enabling real-time data storage and synchronization across multiple clients.
Authentication: A service that simplifies the integration of user authentication and identity management into your application.
Hosting: A service that provides scalable and secure solutions for deploying and serving your web application.
##Mediapipe
Mediapipe is an open-source framework created by Google, equipped with tools for developing real-time computer vision applications.
We selected Mediapipe for its pose detection capabilities, which enable precise estimation of 33 key body landmarks in real time..







  




