# AI-Powered Calculator Web Application

An AI-powered calculator that converts handwritten equations into digital form, solves mathematical problems, and detects abstract concepts in drawings. This application combines a FastAPI backend with a React-based frontend, utilizing multiple libraries for drawing, equation recognition, and rendering LaTeX expressions.

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Running the Project](#running-the-project)
- [Deployment](#deployment)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Converts handwritten mathematical expressions into LaTeX.
- Solves complex mathematical problems.
- Detects and interprets abstract concepts in drawings.
- Provides interactive drawing tools for users.
- Real-time updates and rendering of the LaTeX mathematical expressions.

## Technology Stack
- **Frontend**: React.js, Mantine UI, Draggable, Canvas API
- **Backend**: FastAPI, Uvicorn
- **Libraries**: MathJax for rendering LaTeX, Axios for HTTP requests
- **Styling**: Tailwind CSS

## Prerequisites
Before you begin, ensure you have the following software installed:
- [Node.js](https://nodejs.org/) and npm
- [Python 3.x](https://www.python.org/)
- [pip](https://pip.pypa.io/en/stable/installation/)
- [FastAPI](https://fastapi.tiangolo.com/)
- [Uvicorn](https://www.uvicorn.org/)
- [Nginx](https://nginx.org/en/) (for deployment)
- [Git](https://git-scm.com/) for version control

## Project Structure
. ├── frontend/ # Frontend codebase │ ├── public/ # Static files │ ├── src/ # Source code │ └── package.json # Frontend dependencies ├── backend/ # Backend codebase │ ├── apps/ # FastAPI application logic │ ├── constants/ # Configuration constants │ ├── main.py # Entry point for FastAPI │ └── requirements.txt # Backend dependencies ├── README.md # Project documentation └── .env # Environment variables

bash
Copy code

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ai-powered-calculator.git
cd ai-powered-calculator
2. Backend Setup
Navigate to the backend directory:
bash
Copy code
cd backend
Install Python dependencies:
bash
Copy code
pip install -r requirements.txt
3. Frontend Setup
Navigate to the frontend directory:
bash
Copy code
cd ../frontend
Install Node.js dependencies:
bash
Copy code
npm install
Running the Project
1. Run the Backend Server
bash
Copy code
cd backend
uvicorn main:app --host 0.0.0.0 --port 8000 --reload
2. Run the Frontend Development Server
bash
Copy code
cd frontend
npm run dev
Access the Application
Frontend: http://localhost:3000
Backend API: http://localhost:8000
