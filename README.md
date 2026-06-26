# AI-Resume-Screener-and-Job-Match-Engine 
An intelligent NLP-based candidate screening system that automatically matches resumes to job descriptions using BERT semantic similarity, TF-IDF keyword matching, and skill gap analysis.

##  Features
- Extracts structured info from resumes (name, email, skills, education, experience)
- Parses job descriptions to identify required skills and qualifications
- Computes match score using 4 techniques:
  - 🔵 TF-IDF Cosine Similarity (20%)
  - 🟣 BERT Semantic Similarity (30%)
  - 🟢 Skill Gap Analysis (40%)
  - 🟠 Experience Matching (10%)
- Ranks multiple candidates automatically
- Interactive UI using ipywidgets (works inside Google Colab)
- Visual analytics — bar charts, pie charts, word clouds
- Supports PDF, DOCX, and TXT resume formats


   ##  Tech Stack
| Category | Tools |
|---|---|
| Language | Python 3.12 |
| NLP | spaCy, NLTK |
| AI/ML | Sentence-Transformers (BERT), Scikit-learn |
| File Parsing | PyMuPDF, python-docx |
| Visualization | Plotly, Matplotlib, WordCloud |
| UI | ipywidgets |
| Platform | Google Colab |

 


