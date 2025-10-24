**Updated Readme to Read The Completed Project**

**WeatherWise : AI-Powered Weather Assistant**
WeatherWise is a Python-based weather assistant built in Google Colab. It interprets natural-language questions, fetches real-time weather data via the fetch_my_weather library, and displays results as clear text or visual charts. The project demonstrates Python integration of APIs, basic NLP parsing, and data visualization in an interactive, user-friendly workflow.

**Features**
•	Natural Language Parsing: Understands user questions such as “What’s the weather in Perth tomorrow?”
•	Live API Integration: Retrieves data directly from fetch_my_weather with JSON or text output.
•	Visual Forecasts: Generates temperature and precipitation charts using Matplotlib.
•	Error Handling: Detects invalid inputs and provides user-friendly messages.
•	Manual & AI Modes: Switch between guided menu input and conversational querying.

**Program Structure**
weatherwise/
generate_weather_response()   # entry point / main function
•	get_we	ather_data()           # Retrieves weather data from API
•	parse_weather_question()     # Extracts location and forecast intent using NLP
•	create_temperature_visualisation()   # visualizes temperature forecast
•	create_precipitation_visualisation()  # visualizes precipitation forecast

**Installation & Usage**
Run the notebook in Google Colab or any Python 3.10+ environment:
pip install fetch_my_weather pyinputplus matplotlib hands-on-ai
Then open the Colab notebook and execute all cells.
When prompted:
•	Choose Mode: Manual or Conversation Mode or Exit App
•	Enter a location name (e.g., “Perth”)
•	Choose JSON or text display
•	View optional visualizations

**Learning Outcomes**
This project reinforces:
•	Working with external APIs and JSON data
•	Using regex and NLP for input parsing
•	Building modular Python functions
•	Visualizing forecasts for better user interpretation

**AI Assistance**
ChatGPT & Gemini supported design refinement, debugging (e.g., missing prompt issue), and visualization logic. Prompts were intentionally crafted to explain reasoning, test assumptions, and improve efficiency. AI conversations are kept in ai conversation folders as text files. 


**Instructor Provided Reaadme FIle**

# 🌦️ WeatherWise Template

Welcome to the **WeatherWise Assignment Starter Template**! This repository helps you kickstart your project by combining Python, weather APIs, data visualisation, and AI-assisted development. 🤖📊

![Build With AI](https://img.shields.io/badge/Built_with-AI-blueviolet?logo=openai)
![Python](https://img.shields.io/badge/Made_with-Python-3776AB?logo=python)
![Visualisation](https://img.shields.io/badge/Includes-Visualisations-orange?logo=plotly)

---

## 🚀 How to Use This Template

1. Click **"Use this template"** on GitHub to create your own copy.
2. Rename your repository to something like `weatherwise-jane-doe`.
3. Clone it and start developing in `starter_notebook.ipynb`.

---

## 📁 Folder Structure

- `starter_notebook.ipynb` — Main notebook to build your project.
- `ASSIGNMENT.md` — Full assignment specification.
- `ai-conversations/` — Save your `.txt` AI conversations here.
- `resources/` — Guides, prompting tips, and AI technique examples.
- `submission/` — Files to help you finalise your submission:
  - `checklist-md.md` — Submission checklist
  - `reflection.md` — Write your 300–500 word project reflection
  - `one-page-summary.md` — (Optional) Your own summary of key ideas or process

---

📄 **Quick Overview:**  
A one-page summary of the full assignment is available in [`resources/assignment-summary.md`](resources/assignment-summary.md).

---

## 📓 Submission Checklist

✅ Complete all required functions  
✅ Include at least 5 AI conversations in `ai-conversations/`  
✅ Document your intentional prompting  
✅ Fill in your project reflection in `submission/reflection-template.md`  
✅ Zip your project and upload it to the LMS  

---

🧠 AI Conversations  
Save your AI interactions in the `ai-conversations/` folder.  
See `ai-conversations/how-to-log-ai-conversations.md` for details.


--
## 🧠 Need Help with AI Prompts?

Check out:
Check out:
- `resources/ai-tips-tricks.md` — Prompting tips and pitfalls
- `resources/sample-prompting-journey.md` — Full example of AI-enhanced development
- `resources/prompts-by-method-step.md` — Prompts aligned with the 6-step dev process
- `resources/before-after-example.md` — Required: Show how your prompting improved AI-generated code


Good luck and have fun! 💡🌤️
