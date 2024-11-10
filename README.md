# Team Name: ProfFinder

This AI-powered Rate My Professor website allows users to obtain detailed insights into a professor's teaching style, grading tendencies, and overall ratings based on data scraped from RateMyProfessor. Users can enter a professor's RateMyProfessor link, and the site leverages a custom-built web scraping system to extract data such as ratings, student comments, and other key metrics. This data is then analyzed by a generative AI-powered chatbot, which answers user questions and provides insights based on real student feedback, including average grades, common student concerns, and the professor's strengths.

The software is built using Next.js, React, and Firebase for frontend functionality, while the backend leverages Spring Boot and the OpenAI API (through DeepInfra). The application also includes a user authentication system using Firebase, allowing users to save their chat history with the chatbot and rename chats for easy reference.

Key Features
Professor Data Scraping: Scrapes relevant information from RateMyProfessor pages based on the provided link.
AI-Powered Insights: Uses OpenAI’s generative AI to analyze and provide responses based on scraped data, including professor ratings, comments, and student feedback.
Customizable Chat History: Allows users to save and rename chats, facilitating organization and easy access to prior insights.
Responsive Design: Optimized for various device sizes to ensure a smooth user experience.
Technology Stack
Frontend: React, Next.js
Backend: Spring Boot
Data Scraping: Custom scraping functions using JavaScript and axios
Generative AI: OpenAI API (via DeepInfra)
Authentication & Database: Firebase
Unit Testing
The project includes unit tests to ensure data retrieval and error handling in the core getProfessorData function. These tests, written with Jest, verify that professor data is accurately fetched and that appropriate errors are raised when data retrieval fails.
