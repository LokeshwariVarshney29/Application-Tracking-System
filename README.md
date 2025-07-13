# 🤖 Intelligent ATS Resume Expert

An AI-powered resume analysis tool that leverages Google's Gemini AI to evaluate resumes against job descriptions, providing professional HR insights and percentage matching scores for better job application success.

## 📌 Project Overview

This Streamlit-based web application acts as an intelligent Applicant Tracking System (ATS) that helps job seekers optimize their resumes by:
- Analyzing resume content against specific job descriptions
- Providing professional HR feedback on strengths and weaknesses
- Calculating percentage match scores between resume and job requirements
- Identifying missing keywords and skills

## 🚀 Key Features

### 1. AI-Powered Resume Analysis
- **Google Gemini Integration**: Uses Google's Gemini 1.5 Flash model for intelligent content analysis
- **PDF Processing**: Extracts and processes PDF resumes using PyMuPDF
- **Image Conversion**: Converts PDF pages to images for AI analysis
- **Base64 Encoding**: Handles file encoding for seamless AI processing

### 2. Dual Analysis Modes
- **Professional Review**: Comprehensive HR-style evaluation with strengths/weaknesses analysis
- **Percentage Matching**: Quantitative scoring with missing keywords identification
- **Multi-Domain Support**: Covers Data Science, Full Stack, Web Development, Big Data Engineering, DevOps, and Data Analyst roles

### 3. Interactive Web Interface
- **Streamlit Framework**: Clean, user-friendly web interface
- **Real-time Processing**: Instant analysis and feedback
- **File Upload**: Easy PDF resume upload functionality
- **Responsive Design**: Works across different devices and screen sizes

### 4. Comprehensive Feedback System
- **Detailed Evaluation**: Professional HR insights on candidate alignment
- **Keyword Analysis**: Identifies missing technical skills and keywords
- **Actionable Recommendations**: Provides specific improvement suggestions
- **Percentage Scoring**: Quantifies resume-job description compatibility

## 🛠️ Technical Stack

- **Frontend**: Streamlit
- **AI/ML**: Google Generative AI (Gemini 1.5 Flash)
- **PDF Processing**: PyMuPDF (fitz)
- **Image Processing**: Base64 encoding
- **Environment Management**: python-dotenv
- **Language**: Python

## 📂 Project Structure

```
Intelligent-ATS-Resume-Expert/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Python dependencies
├── .env                  # Environment variables (API keys)
└── README.md             # Project documentation
```

## 🔧 Installation & Setup

### Prerequisites
- Python 3.7 or higher
- Google API Key for Gemini AI

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd Intelligent-ATS-Resume-Expert
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the project root
   - Add your Google API key:
     ```
     GOOGLE_API_KEY=your_google_api_key_here
     ```

4. **Run the application**:
   ```bash
   streamlit run app.py
   ```

## 💡 How to Use

### Step 1: Launch Application
- Run the Streamlit app using `streamlit run app.py`
- Open your browser to the provided local URL

### Step 2: Input Job Description
- Enter the target job description in the text area
- Include key requirements, skills, and qualifications

### Step 3: Upload Resume
- Click "Upload Resume (PDF)" button
- Select your PDF resume file
- Wait for upload confirmation

### Step 4: Choose Analysis Type
- **"Tell Me About the Resume"**: Get comprehensive HR feedback
- **"Percentage Match"**: Get quantitative matching score and missing keywords

### Step 5: Review Results
- Analyze the AI-generated feedback
- Implement suggested improvements
- Retest with updated resume

## 🔍 Use Cases

- **Job Seekers**: Optimize resumes for specific job applications
- **Career Counselors**: Provide data-driven resume improvement advice
- **HR Professionals**: Pre-screen candidates efficiently
- **Students**: Prepare resumes for internships and entry-level positions
- **Career Changers**: Align resumes with new industry requirements

## ⚙️ Technical Implementation

### PDF Processing Pipeline
1. **File Upload**: Streamlit file uploader handles PDF input
2. **PDF Reading**: PyMuPDF opens and processes PDF documents
3. **Image Conversion**: First page converted to image format
4. **Base64 Encoding**: Image data encoded for AI processing
5. **AI Analysis**: Gemini AI analyzes image and text content

### AI Prompt Engineering
- **Prompt 1**: HR professional evaluation with strengths/weaknesses
- **Prompt 2**: Percentage matching with keyword gap analysis
- **Context-Aware**: Prompts tailored for tech industry roles

## 🚀 Future Enhancements

- **Multi-page PDF Support**: Analyze complete resume documents
- **Industry-Specific Analysis**: Expand to more job domains
- **Resume Optimization Suggestions**: Automatic content improvements
- **Batch Processing**: Handle multiple resumes simultaneously
- **Export Functionality**: Save analysis reports as PDF/Word
- **Integration APIs**: Connect with job boards and ATS systems
- **Analytics Dashboard**: Track resume performance over time

## 🔒 Security & Privacy

- **API Key Protection**: Environment variables for sensitive data
- **File Handling**: Secure PDF processing without permanent storage
- **Data Privacy**: No resume data stored permanently
- **Error Handling**: Comprehensive exception management

## 📊 Supported Job Roles

- Data Science
- Full Stack Development
- Web Development
- Big Data Engineering
- DevOps Engineering
- Data Analysis

## 🧪 Testing

Test the application with:
- Various PDF resume formats
- Different job descriptions
- Multiple technical domains
- Edge cases (corrupted PDFs, missing content)

## 👩‍💻 Author

**Lokeshwari Varshney**

AI/ML Enthusiast & Software Developer
