# Audio-to-Text Application

Welcome to the Audio-to-Text Application! This project consists of two parts: a Spring Boot backend and a React frontend. The application allows users to upload audio files and get a transcription of the audio content.

## Repository Structure

- `backend/` - Contains the Spring Boot application.
- `frontend/` - Contains the React application.

## Getting Started

### Prerequisites

- Java 21 or later
- Node.js and npm (Node Package Manager)

### Backend Setup

1. Navigate to the `backend` directory:
   ```bash
   cd backend
Ensure that you have the required dependencies:
bash
Copy code
./mvnw clean install
Create an .env file in the backend directory with the following content:
env
Copy code
spring.ai.openai.api-key=YOUR_OPENAI_API_KEY
Run the Spring Boot application:
bash
Copy code
./mvnw spring-boot:run
The backend server will start on http://localhost:8080.
Frontend Setup
Navigate to the frontend directory:
bash
Copy code
cd ../frontend
Install the required dependencies:
bash
Copy code
npm install
Start the React application:
bash
Copy code
npm start
The frontend application will open in your browser at http://localhost:3000.
Usage

Open the React application in your browser.
Upload an audio file using the file input.
Click the "Upload and Transcribe" button.
The transcription result will be displayed on the page.
Folder Structure

backend/
src/ - Contains the source code of the Spring Boot application.
pom.xml - Maven configuration file.
frontend/
src/ - Contains the source code of the React application.
package.json - Node.js package configuration file.
License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements

Spring Boot for the backend framework.
React for the frontend library.
OpenAI for the transcription service.
sql
Copy code

You can replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key and update any
