**🤖 AI Resume Screening & Feedback Workflow**

**📌 Project Overview**

This project is an automated AI-powered Resume Screening System built using workflow automation. It processes candidate resumes, extracts key information, evaluates them against job requirements, and stores results while notifying HR.

The system reduces manual effort, speeds up hiring, and ensures consistent candidate evaluation.

**🚀 Features**
📄 Upload resume (PDF)
🔍 Extract candidate information automatically
🧠 AI-based resume analysis using LLM
📊 Generate summarized candidate insights
👨‍💼 HR-level evaluation & scoring
📑 Store results in Google Sheets
📧 Send automated email notifications
📝 Update structured documents

**🛠️ Tech Stack**
Workflow Automation Tool (e.g., n8n / similar)
LLM Integration (Google Gemini API)
Google Drive – File storage
Google Sheets – Data logging
Email Service – Notifications
PDF Parser – Resume extraction

**⚙️ Workflow Architecture**
  Step-by-Step Flow:
1.Trigger:
Starts on form submission

2.File Upload:
Resume is uploaded to Google Drive

3.Extract from File:
PDF content is extracted

4.Parallel Processing:
Candidate Details Extraction
Information Extraction

5.Merge Node:
Combines extracted data

6.Summarization Chain:
AI summarizes candidate profile

7.HR Expert Evaluation:
AI evaluates candidate suitability
Generates structured output

8.Final Actions:
Append data to Google Sheets
Update document
Send email notification

**📊 Output Example**
Candidate Name
Skills
Experience
Match Score
Strengths & Weaknesses
Final Recommendation

**🔐 Setup Instructions**

**1. Clone Repository**
git clone https://github.com/urvashi772/ai-resume-screening.git
cd ai-resume-screening
**2. Configure API Keys**
Add your Google Gemini API Key
Configure credentials in workflow tool
**3. Connect Services**
Google Drive
Google Sheets
Email (SMTP / Gmail)
**4. Import Workflow**
Import JSON file into your workflow tool
**5. Run Workflow**
Trigger using form submission or manual run

**📁 Project Structure**
├── README.md
├── workflow.json
├── assets/
│   └── workflow.png

**🎯 Use Cases**
HR Automation
Resume Filtering
Candidate Pre-screening
Hiring Pipelines
AI-based Recruitment Systems

**⚠️ Limitations**
Depends on resume format quality
AI responses may vary
Requires API quota management

**🔮 Future Improvements**
Add ATS scoring system
Multi-job comparison
Dashboard visualization
Candidate ranking system

**👩‍💻 Author**
Urvashi Chotaliya

