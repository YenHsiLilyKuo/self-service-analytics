# 💡 Self-Service Analytics: Natural Language to SQL + Visualization

A self-service analytics web app that enables business stakeholders to generate SQL queries and visualizations simply by typing natural language. This app uses the **Olist e-commerce dataset from Kaggle stored in a MySQL database**, The app is powered by a Groq LLM API for query generation, NL4DV for data-to-visual insight mapping, and Streamlit for an intuitive user interface.



## 📌 Key Features

- 🗣️ Translate natural language prompts into SQL queries using the Groq API
- 🧮 Execute SQL queries on a MySQL database (`olist_data`)
- 📊 Automatically visualize results with Altair charts
- 🧠 Enable non-technical users to explore data without writing code
- 🔁 Reusable, fast, and no-code interface


## 🔧 Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python, MySQL
- **NLP-to-SQL**: Groq API
- **Natural Language → Visualization Mapping**: NL4DV, Stanford CoreNLP
- **Visualization**: Altair

## 🖨️   Flyer

[Flyer.pdf](Flyer.pdf)

## 🎥 Demo
<video src="demo1.mp4" controls width="700"></video>
 -->

## 🚀 Run Locally

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Set up MySQL database
Ensure a MySQL instance is running with the olist_data database and your credentials.

### 3. Configure connection
Copy the example config and fill in your info:
```bash
cp config/db_connect.json.example db_connect.json
```

### 4. Run the app
```bash
streamlit run app/main_app.py
```



## 👩‍💻 Team
Yen-Hsi Kuo, Sam Neal, Ruth Hsu, Maggie Wang, Rachel Liang