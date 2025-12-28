# ats-system
AI-powered ATS system that evaluates resumes against job descriptions and generates structured relevance scores, strengths, weaknesses, and hiring insights using LLM reasoning.
🧠 Project Title

AI-Based Applicant Tracking System (ATS) for Digital Marketing Roles

📄 README.md (Complete Description)
🔍 Overview

This project is an AI-powered Applicant Tracking System (ATS) designed to analyze resumes against a given job description and generate a detailed screening report.

The system mimics the decision-making process of an expert recruiter, focusing on:

Skill relevance

Role alignment

Strengths and weaknesses

Overall job fit score

It is especially optimized for Digital Marketing roles, but the structure can be adapted for other domains.

🎯 Key Features

📄 Resume and Job Description analysis

🧠 LLM-based reasoning (no assumptions, content-driven evaluation)

📊 Relevance scoring (0–10 scale)

💪 Strength & ⚠️ weakness identification

🧾 Structured JSON output (easy to integrate with ATS pipelines)

🏗️ Flat JSON response (API & database friendly)

🧩 Output Format

The system returns a single flat JSON object with the following fields:

{
  "candidateName": "",
  "currentOrganization": "",
  "skills": "",
  "phoneNumber": "",
  "emailId": "",
  "location": "",
  "strengths": "",
  "weaknesses": "",
  "relevanceScore": "",
  "justification": ""
}

🛠️ How It Works

Input resume text

Input job description

AI analyzes both using recruiter-level reasoning

Outputs structured screening insights in JSON format

The system strictly avoids guessing and relies only on provided resume content.

🚀 Use Cases

Resume screening automation

Pre-interview candidate shortlisting

Recruiter decision support

HR analytics & hiring pipelines

ATS + LLM integration projects

🧑‍💻 Tech Stack

LLM-based reasoning (prompt-engineered)

JSON-based structured output

Compatible with Python / Node / API workflows

GitHub-ready & modular design

📌 Future Improvements

ATS score visualization dashboard

Multi-role evaluation support

Resume keyword heatmap

PDF resume parsing

Admin panel for recruiters

📜 Disclaimer

This project is intended for educational and research purposes and demonstrates how AI can assist recruiters in improving hiring efficiency.

⭐ If you like this project

Give it a ⭐ and feel free to fork, contribute, or suggest improvements!
