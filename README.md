AI Engineering Job Market Chatbot
This project is a Streamlit application that combines a detailed AI engineering job market dataset with Google's Gemini 2.5 Flash generative AI to provide data-driven insights.

Features
Interactive chat UI built on Streamlit for natural language queries.

Data querying and aggregation from a comprehensive AI job market dataset (ai_job_market.csv), including:

Skills and tools required per role and experience level.

Average salary ranges by role and level.

Industry demand insights.

Skill overlaps between job titles and levels.

Integration with Google Gemini 2.5 Flash model to generate concise, enriched answers based on dataset context.

GitHub issue creation support directly from the app to report issues or feedback.

Sidebar displaying dataset highlights for quick reference.

Dataset
The dataset powers the chatbot's data-driven answers and contains around AI engineering job market data with fields such as:

Job titles (e.g., AI Product Manager, NLP Engineer)

Experience levels (Entry, Junior, Middle, Senior, Lead)

Skills required and preferred tools

Salary ranges (USD)

Industry and location info

Getting Started
Prerequisites
Python 3.8+

Google Cloud project with access to Generative Language API

Google Gemini API key

GitHub personal access token (with repo permissions)

Installation
Clone the repo:

bash
git clone https://github.com/16bitSega/Chat_with_data
cd <repo_directory>
Install dependencies:

bash
pip install -r requirements.txt
Set environment variables in .env file:

text
GEMINI_API_KEY=your_google_gemini_key
GITHUB_TOKEN=your_github_token
GITHUB_REPO=your_github_user/repo_name
Place the ai_job_market.csv dataset in the root directory.

Running the app
Run the Streamlit app locally:

bash
streamlit run main.py
Open the displayed URL (usually http://localhost:8501) to start interacting.

How to Use
Enter free-text questions about AI engineering jobs, e.g.:

"What is the average salary for a mid-level ML engineer?"

"What skills overlap between entry NLP engineer and senior AI product manager?"

"Which industries demand AI researchers?"

Review answers enriched by the dataset and Google Gemini generative AI.

Create GitHub support tickets from the UI if you spot issues or need improvements.

Extending
Add more complex natural language parsing or entity extraction to handle advanced queries.

Extend the dataset with more job roles, geographic data, or time-based trends.

Add visualization dashboards for richer insights beyond conversational Q&A.

License
This project is licensed under the MIT License.
