# AI Resume Critiquer

An AI-powered tool that analyzes your resume and gives **personalized feedback** on how to improve it for any job role.  
Built with **Streamlit** and **Google Gemini 1.5 Flash**, this app reviews resumes like a professional recruiter — clear, structured, and actionable.

---

## Features
- Upload resumes in **PDF** or **TXT** format  
- Automatically extracts and reads resume content  
- Analyzes clarity, skills, and impact of your resume  
- Provides **specific suggestions** for improvement  
- Optional: Tailor feedback for a particular **job role**  
- Simple, clean Streamlit UI  

---

## Setup & Usage

### 1. Clone this repository
```bash
git clone https://github.com/yourusername/AI-Resume-Critiquer.git
cd AI-Resume-Critiquer
```

### 2. Install dependencies
```bash
pip install streamlit google-generativeai PyPDF2
```

### 3. Add your Gemini API key
Open the Python file and replace this line:
```python
GOOGLE_API_KEY = "your_api_key_here"
```
with your actual Gemini API key:
```python
GOOGLE_API_KEY = "YOUR_API_KEY_HERE"
```

*(You can get a free key from [Google AI Studio](https://aistudio.google.com/app/apikey))*

### 4. Run the Streamlit app
```bash
streamlit run app.py
```

---

## How It Works
1. Upload your resume as a PDF or TXT file.  
2. (Optional) Enter your desired **job role** (e.g., Data Scientist, Software Engineer).  
3. Click **Analyze Resume**.  
4. The AI reads your resume and gives detailed feedback covering:  
   - Content clarity and impact  
   - Skill presentation  
   - Experience relevance  
   - Specific suggestions for the job role  

---

## Tech Stack
- **Python**  
- **Streamlit**  
- **Google Gemini API**  
- **PyPDF2** (for PDF text extraction)

---

## License
This project is open-source and free for educational or non-commercial use.

---

*(Created with ❤️ by a developer passionate about AI and automation.)*
