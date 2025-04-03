# AI Resume Builder

## Overview
AI Resume Builder is a web application that utilizes AI to generate tailored, ATS-friendly resumes. It features a React/Daisy UI front-end and a Spring Boot back-end, integrating the Deepseek R1 model (via Ollama) to generate optimized bullet points, skills, and summaries.

## Tech Stack
- **Frontend:** React, Daisy UI
- **Backend:** Spring Boot
- **AI Model:** Deepseek R1 (via Ollama)

## Features
- AI-powered resume generation with ATS-optimized content
- Dynamic bullet points, skill suggestions, and personalized summaries
- User-friendly form-based editor for easy content refinement
- Customizable resume templates for tailored outputs
- Seamless integration between front-end and back-end services

## Installation & Setup
### Backend (Spring Boot)
1. Clone the repository:
   ```sh
   git clone https://github.com/akashpratapsing/AI-Resume-Builder.git
   cd ai-resume-builder
   ```
2. Set up the backend:
   ```sh
   cd backend
   mvn clean install
   mvn spring-boot:run
   ```
3. Ensure the Deepseek R1 model is running via Ollama.

### Frontend (Vite+React)
1. Navigate to the frontend directory:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React app:
   ```sh
   npm run dev
   ```

## Usage
- Open the web application and fill in the required details.
- The AI model generates ATS-friendly resume sections automatically.
- Customize the generated content as needed.
- Download the final resume in a structured format.

## Contribution
Contributions are welcome! Feel free to fork the repo, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License.


