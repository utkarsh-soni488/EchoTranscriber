# EchoTranscriber

**EchoTranscriber** is an advanced audio-to-text application that leverages OpenAI’s Whisper model to convert spoken language into written text seamlessly.

## Features

- Upload audio files in various formats.
- Transcribe audio to text with high accuracy.
- Simple and intuitive user interface.

## Screenshot

### Application Interface

![Application Interface](screenshots/application-interface.png)

## Installation

### Frontend

1. Navigate to the `frontend` directory:
   ```bash
   cd frontend
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm start
Backend
Navigate to the backend directory:
bash
Copy code
cd backend
Build the project:
bash
Copy code
./mvnw clean install
Run the application:
bash
Copy code
./mvnw spring-boot:run
Configuration

Update the application.properties file in the backend directory with your OpenAI API key:

properties
Copy code
spring.application.name=Audio-to-text
spring.ai.openai.api-key=YOUR_OPENAI_API_KEY
spring.ai.openai.audio.transcription.base-url=https://api.openai.com
spring.ai.openai.audio.transcription.options.model=whisper-1
spring.ai.openai.audio.transcription.options.response-format=json
Replace YOUR_OPENAI_API_KEY with your actual API key.

Usage

Open the frontend application in your browser.
Upload an audio file.
Click "Upload and Transcribe" to get the transcription.
Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements.

License

This project is licensed under the MIT License - see the LICENSE file for details.

markdown
Copy code

**Instructions**:
- Make sure to replace `docs/screenshots/application-interface.png` with the actual path and filename of your screenshot.
- Replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key in the configuration section.
