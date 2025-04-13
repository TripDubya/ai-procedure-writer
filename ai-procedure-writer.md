# Initialize git repository

## Setting up a new git repository

git init

## Add all files

git add .

## Commit the files

git commit -m "Initial commit"

## Add the remote repository (replace YOUR_USERNAME with your GitHub username)

git remote add origin https://github.com/TripDubya/ai-procedure-writer.git 

## Push to GitHub

git push -u origin main
# AI Procedure Writer

An AI-powered tool for generating and managing work procedures.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/TripDubya/ai-procedure-writer.git
   cd ai-procedure-writer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run src/gui/streamlit_app.py
   ```

## Features

- Generate detailed work procedures using AI
- Web-based interface using Streamlit
- Search and incorporate web content
- Train the model with custom data

## Project Structure

```text
ai_procedure_writer/
├── src/
│   ├── gui/
│   │   └── streamlit_app.py
│   ├── core/
│   └── utils/
├── requirements.txt
└── README.md
```