# Resume_Parser_NER_Project
# 🧠 Resume Parser using Named Entity Recognition (NER)
# 📌 Objective
The goal of this project is to build an NLP-based system that can automatically extract structured information such as Name, Skills, Degree, Institutions, and Work Experience from raw resumes in .pdf or .txt formats. This simulates a real-world HR automation task and is ideal for streamlining the candidate shortlisting process.

# 🛠️ Tech Stack
Python

spaCy (Named Entity Recognition)

PyMuPDF (fitz) for parsing PDFs

Streamlit / Google Colab (optional UI)

pandas, re, os, json for processing and structuring the output

# 🔍 Extracted Information
👤 Name

🧰 Skills (e.g., Python, Java, SQL)

🎓 Degree

🏫 Institutions

🏢 Work Experience

# 🧪 How It Works
Upload Resume (.pdf or .txt)

Preprocess the Text

Apply spaCy NER Model

Use Rule-Based Matching for domain-specific terms (skills, degrees)

Output Structured Data in JSON or table format

# 🚀 Getting Started
Google Colab
Open the provided .ipynb notebook in Google Colab.

Upload your resume files.

Run the cells to extract structured data.

# Local Setup (Optional)
```
pip install spacy pandas PyMuPDF
python -m spacy download en_core_web_sm
```
# 📁 Example Output

{
  "Name": "John Doe",
  "Skills": ["Python", "Machine Learning", "SQL"],
  "Degree": ["B.Tech"],
  "Institutions": ["IIT Delhi"],
  "Work Experience": ["Software Engineer at Infosys from 2020 to 2023"]
}
# 📈 Future Enhancements
Use Hugging Face transformers for improved NER accuracy

Add support for .docx files

Integrate a web UI with Streamlit

Link to a recruitment dashboard for end-to-end HR automation
