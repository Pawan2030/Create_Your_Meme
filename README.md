# Create Your Meme

Welcome to the **Create Your Meme** project! This application allows you to create and share personalized memes with your loved ones to bring laughter and smiles to their faces.

## Purpose

The primary goal of this application is to make it easy for anyone to create fun and engaging memes. Whether it's for a special occasion or just to brighten someone's day, this tool empowers users to add their own touch to popular meme formats and share them with friends and family.

## Features

- Generate random GIFs using the Giphy API.
- Create custom memes with personalized text.
- Share your memes easily with others.

## Demo


https://github.com/user-attachments/assets/454ebc91-219c-47ab-b26f-7beb1e5b625b



## Installation and Setup

To run this project on your local machine, follow these steps:

### 1. Clone the Repository

Clone this repository to your local machine using the following command:

git clone https://github.com/Pawan2030/Create_Your_Meme.git

### 2. Navigate to the Project Directory
Go to the project folder:
cd Create_Your_Meme

### 3. Install Dependencies
Make sure you have Node.js installed on your system. Then, install the required dependencies:
npm install

### 4. Set Up Environment Variables
Create a .env file in the root directory and add your Giphy API key:
REACT_APP_GIPHY_API_KEY=your_giphy_api_key_here

### 5. Run the Application
Start the development server:
npm start

The application will start running on http://localhost:3000.

### 6. Build for Production
To create a production-ready build of the application:
npm run build

## Project Structure
Here is a brief overview of the project's structure:

src/: 
Contains the source code for the application.

components/: 
React components used in the application.

hooks/:
Custom hooks, including the useGif hook to fetch random GIFs.

index.js:
Entry point of the application.

index.css:
Global styles for the application.

public/:
Public assets like images and the main HTML file.

tailwind.config.js:
Configuration file for Tailwind CSS.

.env: 
Environment variables file (not included in the repository for security reasons).

Usage
Create your meme: Generates random GIFs using the Giphy API. Click the "Generate" button to get a new GIF.
Create Meme: Customize a meme with your own text and share it with others.

### Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request.


