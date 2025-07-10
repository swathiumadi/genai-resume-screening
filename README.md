# genai-resume-screening
A Generative AI project to classify resumes using Hugging Face zero-shot classification
#  GenAI Resume Classifier 

This project leverages **Generative AI (Zero-Shot Learning)** to automatically classify resumes into job roles such as Data Science, DevOps, HR, and more — **without any training**. It uses the powerful **`facebook/bart-large-mnli` model** from Hugging Face and runs entirely on **Google Colab** using Python.

---

##  Project Overview 

Recruiters often spend hours manually reading and sorting resumes. This project solves that by automating the classification using a **zero-shot classification model**, which understands and labels raw resume content without needing labeled training data.

---

##  Objectives 

- Classify resumes into predefined job categories using GenAI  
- Eliminate the need for model training (Zero-shot learning)  
- Run everything using free tools (Google Colab + Hugging Face)

---

## Tools & Technologies

| Tool/Library | Purpose |
|--------------|---------|
| Google Colab | Development & execution environment |
| Python       | Programming language |
| Hugging Face Transformers | Load BART model |
| facebook/bart-large-mnli | Zero-shot classification model |
| pandas       | Data handling (CSV, DataFrames) |
| re (regex)   | Text cleaning |
| tqdm         | Loop progress bar |

---

##  Project Files 

| File | Description |
|------|-------------|
| `Resume.csv` | Input resume dataset (cleaned or zipped) |
| `resume_classifier.ipynb` | Google Colab notebook with full GenAI code |
| `GenAI_Classified_Resumes.csv` | Output file with predicted job roles |
| `Project_Report.docx` | Project report in specified format |
| `README.md` | This file |

---

##  Sample Output

| Resume Snippet | Predicted Role |
|----------------|----------------|
| ...python, pandas, ML... | Data Science |
| ...design, photoshop...  | Design |
| ...hr recruiter, payroll... | HR |

---


##  Dataset Notice 

The dataset file is over **25 MB**, it is be uploaded in a **compressed (.zip)** format due to GitHub limitations. Unzip it before use.
 

---

 

