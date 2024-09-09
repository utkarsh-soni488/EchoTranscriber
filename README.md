# EchoTranscriber

**EchoTranscriber** is an advanced audio-to-text application that leverages OpenAI’s Whisper model to convert spoken language into written text seamlessly.

## Features

- Upload audio files in various formats.
- Transcribe audio to text with high accuracy.
- Simple and intuitive user interface.


## Installation

### Frontend


# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm start

BACKEND

# Navigate to the backend directory
cd backend

# Build the project
./mvnw clean install

# Run the application
./mvnw spring-boot:run

Configuration

Update the application.properties file in the backend directory with your OpenAI API key:
# Open the application.properties file
nano src/main/resources/application.properties

spring.application.name=Audio-to-text
spring.ai.openai.api-key=YOUR_OPENAI_API_KEY
spring.ai.openai.audio.transcription.base-url=https://api.openai.com
spring.ai.openai.audio.transcription.options.model=whisper-1
spring.ai.openai.audio.transcription.options.response-format=json
Replace YOUR_OPENAI_API_KEY with your actual API key.
