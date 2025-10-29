# RecipeShare App

A modern web application for sharing and discovering recipes. This app allows users to create accounts, upload their own recipes with photos, and browse a public gallery of all submissions. It features an AI-powered scanner to read ingredients and directions from photos, making recipe entry a breeze.

# Features

User Authentication: Secure sign-up and sign-in with Email/Password or Google.

Public Recipe Gallery: Browse all user-submitted recipes in one place.

Clickable Recipe Details: Click any recipe to see a pop-up modal with the full photo, ingredients, and directions.

Add New Recipes: A clean, tabbed form for adding new recipes.

Cloudinary Photo Uploads: Upload recipe photos directly to the cloud with a simple drag-and-drop interface.

AI-Powered OCR: Uses the Gemini AI API to scan photos of cookbooks or handwritten notes and automatically fill in the "Ingredients" and "Directions" text boxes.

Technologies Used

Frontend: HTML5, Tailwind CSS, and modern JavaScript.

Backend (BaaS):

Firebase Authentication: For managing user login and sign-up.

Firestore Database: For storing all recipe text data (titles, ingredients, etc.) in real-time.

Image Hosting:

Cloudinary: For all recipe photo uploads and hosting.

AI:

Google Gemini AI: For the OCR (Optical Character Recognition) feature.

Getting Started

To run this project locally, you will need to:

Clone this repository.

Open the index.html file in your browser.

You will need to provide your own API keys for:

Firebase: A __firebase_config object in your environment.

Cloudinary: A CLOUDINARY_CLOUD_NAME and CLOUDINARY_UPLOAD_PRESET.

Gemini AI: A geminiApiKey.

Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
