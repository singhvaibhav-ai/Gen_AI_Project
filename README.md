# AI Interview Strategist

![MERN Stack](https://img.shields.io/badge/MERN-Stack-blue?style=for-the-badge&logo=mongodb)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-API-orange?style=for-the-badge&logo=google)

A full-stack application that analyzes candidate resumes against target job descriptions to generate personalized, day-by-day interview preparation roadmaps, mock questions, and tailored ATS-friendly resumes.

## Features

- **Intelligent Resume Analysis:** Upload your resume and a target job description to get a comprehensive match score and skill gap analysis.
- **Personalized Roadmaps:** Receive a dynamic, day-by-day preparation roadmap tailored to your specific weaknesses and the job's requirements.
- **Mock Questions:** Generates highly relevant technical and behavioral questions with interviewer intentions and ideal model answers.
- **AI Resume Tailoring (PDF Generator):** Uses Google Gemini and Puppeteer to rewrite, format, and instantly download a perfectly tailored, ATS-compatible PDF resume.
- **Secure Authentication:** Full JWT-based user authentication and protected routing.

## Tech Stack

**Frontend:**
- React.js (Vite)
- SCSS / SASS

**Backend:**
- Node.js & Express.js
- MongoDB & Mongoose
- Google GenAI API
- Puppeteer (Automated PDF Rendering)
- Zod (Strict JSON Schema Validation)
- Multer (In-memory file uploads)
- JSON Web Tokens (JWT)

## Local Setup

Follow these instructions to run the project locally on your machine.

### 1. Clone the repository
```bash
git clone https://github.com/singhvaibhav-ai/Gen_AI_Project.git
cd Gen_AI_Project
```

### 2. Backend Setup
Navigate to the backend directory and install dependencies:
```bash
cd Backend
npm install
```
Create a `.env` file in the `Backend` directory and add the following variables:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_jwt_key
GOOGLE_GENAI_API_KEY=your_google_gemini_api_key
```
Start the backend server:
```bash
npm run dev
```

### 3. Frontend Setup
Open a new terminal window, navigate to the frontend directory, and install dependencies:
```bash
cd Frontend
npm install
npm run dev
```

### 4. Usage
Open your browser and navigate to `http://localhost:5173`. Create an account, upload your resume (PDF/DOCX), paste a target job description, and start strategizing!

## Contributing
Contributions, issues, and feature requests are welcome!

## License
This project is open source and available under the MIT License.
