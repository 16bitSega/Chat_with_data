<p align="center"> <img src="assets/ai_job_market_banner.png" alt="AI Job Market Insights Banner" width="70%"> </p>
Chat with Data: AI Engineering Job Market Insights
![Python](https://img.shields.io/badgehttps://img.shields.io/badge/Streamlit-%E2%9C%85-brighthttps://img.shields.io/badge

Welcome! This Streamlit app lets you explore the 2025 AI engineering job market using real-world data and the power of Google Gemini generative AI. Instantly get insights about skills, tools, salaries, industries, and job requirements—all through simple natural language chat!

🚀 Features
🤖 Conversational Q&A about AI and data roles, powered by Google Gemini LLM

📊 Analysis of dataset-driven skills, requirements, tools, salary ranges, and industries

🔍 Skill overlap and role comparison queries supported

📝 Create GitHub support tickets directly from the UI

🧑‍💻 Modern sidebar with dataset highlights for quick reference

📺 Demo
![App Screenshot](screenshots/screenshot.jpg Highlights

Experience Levels: Entry, Junior, Middle, Senior, Lead

Job Roles:

AI Product Manager

AI Researcher

Computer Vision Engineer

Data Analyst

Data Scientist

ML Engineer

NLP Engineer

Quant Researcher

Other Columns: Required skills, preferred tools, salary (USD), region, industry

🛠️ Installation
Clone the Repo

bash
git clone https://github.com/<your_user>/<repo>.git
cd <repo>
Install dependencies

bash
pip install -r requirements.txt
Create .env file in project root:

text
GEMINI_API_KEY=your_google_gemini_key
GITHUB_TOKEN=your_github_token
GITHUB_REPO=your_github_user/repo_name
Add dataset:
Place ai_job_market.csv in the root directory.

▶️ Running the App
bash
streamlit run main.py
Visit the printed localhost URL and interact via the browser UI.

💡 How to Use
Ask any question about roles, skills, salaries, or AI job market trends:

What is the average salary for a middle ML engineer?

What skills overlap between entry NLP engineer and middle AI Product Manager?

Which industries demand AI researchers most?

Review answers and dataset-driven breakdowns.

Submit GitHub bug reports or feature requests from the web UI.

🌟 Example Questions
Which industries demand Data Scientists most?

What skills are required for a junior Computer Vision Engineer?

What is the average salary of a senior AI Product Manager?

Which tools are essential for an entry-level NLP Engineer?

What skills overlap between Data Analyst and Data Scientist?

💻 Extending
Add more role/industry mappings, user analytics, or charts

Expand dataset for other regions or years

Enhance the prompt logic for more advanced question types

📄 License
MIT
