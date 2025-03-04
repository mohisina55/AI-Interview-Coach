# AI-Interview-Coach


## Overview
AI Interview Coach is a Streamlit-based web application that generates interview questions based on the selected role, company, topic, difficulty level, and type of interview. It also provides AI-powered feedback on the user's responses.

## Features
- Generate interview questions tailored to your role, company, and topic.
- Select question difficulty: Easy, Medium, or Hard.
- Choose the type of interview (Technical, HR, Behavioral, etc.).
- Receive AI-generated feedback on your answers.
- User-friendly interface with an interactive layout.

## Installation

### Prerequisites
Make sure you have Python installed (version 3.7+).

### Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/AI-Interview-Coach.git
   cd ai-interview-coach
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
### Configuration
1. Set up the Gemini API key:
  -Create a .env file in the root directory.
  -Add the following line:
    ```sh
    GENAI_API_KEY=your_api_key_here

-Replace your_api_key_here with your actual API key.

### Usage
- Run the Streamlit application:
  ```sh
  streamlit run ai_interview_coach.py

### Technologies Used
- Python
- Streamlit
- Google Gemini AI API
- dotenv (for environment variables)

### Project Structure
    ```sh
    📂 AI-Interview-Coach
     ┣ 📜 ai_interview_coach.py             # Main application file
     ┣ 📜 requirements.txt     # Required Python dependencies
     ┣ 📜 .env                 # API key storage (not included in repo)
     ┣ 📜 README.md            # Project documentation

### Future Enhancements

- Store user responses and feedback history.
- Add support for multiple question categories.
- Implement voice-based question answering.

### License
This project is licensed under the MIT License.

### Contributing
Feel free to submit pull requests or open issues for improvements!










   
   

