# Mood of the Queue 🎭

A Streamlit application for tracking and visualizing the emotional vibe of patient support tickets.

![App Screenshot](screenshot.png) *(optional: add screenshot later)*

## Features ✨
- Log ticket queue moods with emoji selection (😊 😐 😠 😕 😟)
- Add optional notes for context
- Automatic timestamp recording
- Real-time visualization of daily mood trends
- Google Sheets backend for data storage

## Prerequisites 🛠️
- Python 3.7+
- Google Cloud Project with:
  - Google Sheets API enabled
  - Service account credentials

## Installation 📥
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mood-of-the-queue.git
   cd mood-of-the-queue
2. Set Up a Virtual Environment
   ```bash
   python -m venv venv
Run the following commands in your Mac Terminal or Windows Command

Step 1: Clone the Repository

git clone https://github.com/qiaozhou-qz/Mochi_Health_Assignment.git

cd Mochi_Health_Assignment

Step 2: Set Up a Virtual Environment 

python -m venv venv(if python3 is installed, use python3; use this line of command to check if python3 is installed: python3 --version)

On windows: venv\Scripts\activate

On Mac: source venv/bin/activate

Step 3: Install Dependencies

pip install -r requirements.txt

Step 4: Run the Streamlit App

streamlit run app.py
