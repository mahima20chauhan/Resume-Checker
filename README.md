# 📄 AI Resume Checker & Job Recommender

This is a **Streamlit-based web application** that analyzes how well your resume matches a given job description. It provides a match score, visual insights, and improvement suggestions using basic NLP techniques.

---

## 🚀 Features

- Upload your resume in PDF format
- Paste job description text
- Get a **match percentage score**
- Visual insights via pie chart
- Intelligent suggestions for improvement
- Clean, attractive UI with custom background and fonts

---

## 📸 Screenshots

### ✨ Home Page with Background

![Home Page](./Screenshot%202025-06-04%20223552.png)

### 📊 Match Score and Analysis

![Match Analysis](./Screenshot%202025-06-04%20223652.png)

---

## 🧠 How It Works

1. Extracts text from the uploaded resume (PDF).
2. Preprocesses resume and job description text.
3. Uses a simple cosine similarity-based model to compare.
4. Displays:
   - Match Score
   - Pie Chart (Match vs Missing Skills)
   - Recommendations

---

## 🛠️ Tech Stack

- Python 🐍
- Streamlit 📊
- Scikit-learn 🔍
- Matplotlib & Seaborn 🎨
- NLP (TF-IDF + Cosine Similarity)
- Custom CSS for styling

---

## 📁 Project Structure

resume-matcher/
│
├── app.py # Streamlit app
├── model.py # Matching logic
├── utils.py # Text extraction and preprocessing
├── styles.css # Custom styles (background, fonts)
├── requirements.txt # Dependencies
├── Screenshot 2025-06-04 223552.png
├── Screenshot 2025-06-04 223652.png
└── README.md

yaml
Copy
Edit

---

## 🎨 Styling Customization

- Custom background image: `bg rp.png`
- Fonts improved for clarity and presentation
- Used `st.markdown()` to inject CSS

---

## 🧾 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
▶️ Running the App
bash
Copy
Edit
streamlit run app.py
Then open the link in your browser (usually: http://localhost:8501)

A project to help job seekers understand resume relevance.

📃 License
MIT License – feel free to use and modify!

vbnet
Copy
Edit

Let me know if you'd like this README.md exported as a `.md` file or zipped with your screenshots for GitHub upload.
