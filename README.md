# PlantPal
A mobile app that connects gardeners to help each other with watering plants. Similar to Rover, but for plant care, with a paid service model.

Tech Stack:
	• Frontend: React Native
	• Backend: Node.js with Express
	• Database: MongoDB
	• Authentication: Firebase Authentication
	• Payment Integration: PayPal API
	• Notifications: Firebase Cloud Messaging (FCM)
	• Hosting: Heroku
	• Version Control: GitHub

Key Features:
	• User Profiles: Gardeners can create profiles showcasing their experience, photos of past work, and plant-care skills.
	• Job Listings: Users can post jobs to find someone to water their plants.
	• Payment System: PayPal integration to handle payments for services.
	• Notifications: Reminder notifications to users and gardeners for watering schedules.
	• Ratings & Reviews: Option to rate gardeners and provide feedback on their service.
	• Search/Filter: Gardeners can search for jobs based on location, plant type, and availability.

Project Roadmap:
Phase 1: Setup and Core Features
	1. Frontend: React Native Setup
		○ Set up a new React Native project using Expo or React Native CLI.
		○ Design basic screens: user registration/login, job listing page, profile setup, and basic navigation.
	2. Backend: Node.js & Express Setup
		○ Set up a Node.js project with Express.
		○ Create RESTful API routes for user registration, job posting, job listing, etc.
		○ Integrate Firebase Authentication for user authentication (sign-up/sign-in).
	3. Database: MongoDB Setup
		○ Set up MongoDB using mongoose for the data models (user profiles, job listings, reviews).
		○ Create models for User, Job, and Reviews with necessary fields.
		○ Set up MongoDB Atlas or a local MongoDB database.
	4. Payment Integration: PayPal API
		○ Integrate PayPal API to handle payments for plant watering services.
		○ Allow users to pay gardeners securely within the app.
Phase 2: Enhancing User Experience
	1. Notifications: Firebase Cloud Messaging (FCM)
		○ Integrate FCM to send notifications about job updates and watering reminders.
		○ Send push notifications to gardeners when a new job is posted and when a watering reminder is due.
	2. Search & Filter Functionality
		○ Implement search and filter functionality for job listings based on location, plant type, and availability.
	3. User Ratings & Reviews
		○ Allow users to rate gardeners after a job is completed and leave reviews.
		○ Display ratings on gardener profiles.
Phase 3: Testing & Deployment
	1. Test Functionality
		○ Perform thorough testing on both iOS and Android devices.
		○ Test payment flow, notifications, user registration, and job posting.
	2. Deployment
		○ Deploy the backend to Heroku.
		○ Publish the app to App Store and Google Play Store.
	3. Version Control
	• Set up a GitHub repository for version control.
	• Make sure to commit regularly and keep your project organized.
Phase 4: Future Enhancements
	• Recurring Payment: Add functionality for recurring payments for users who need constant plant care.
	• Social Features: Add social sharing, so users can share their plants, jobs, or gardening tips.
	• Advanced Filtering: Allow gardeners to specify what type of plants they specialize in (e.g., indoor plants, succulent care).

Project Milestones:
	1. Milestone 1 – Set up the frontend (React Native) and backend (Node.js with Express), and get the basic user registration and job listing functionality working.
	2. Milestone 2 – Implement MongoDB database and PayPal integration for payments, and set up basic notifications with Firebase.
	3. Milestone 3 – Add advanced features like user reviews, ratings, and search functionality. Deploy the app to the App Store and Google Play.
	4. Milestone 4 – Final testing, bug fixes, and future enhancements (recurring payments, social features, etc.).

Getting Started:
	1. Frontend Setup:
		○ Install React Native CLI or Expo:
npm install -g expo-cli
		○ Create a new project:
expo init plant-pal
	2. Backend Setup:
		○ Install Node.js and Express:
npm init -y
npm install express mongoose dotenv
	3. Firebase Authentication Setup:
		○ Create a Firebase project at Firebase Console.
		○ Install Firebase SDK in your React Native app:
npm install firebase
	4. PayPal Setup:
		○ Set up PayPal's developer account and get the Client ID and Secret for integration.
![image](https://github.com/user-attachments/assets/6a394436-d91f-4863-b6ab-433159ce2504)

