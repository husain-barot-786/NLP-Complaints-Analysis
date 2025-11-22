# NLP Complaint Topic Analysis Project

This portfolio project uses Natural Language Processing (NLP) and unsupervised Machine Learning to analyze municipal complaint texts, extracting key topics and presenting them to support data-driven decision making.

---

# Project Directory Structure

```
NLP-Complaints-Analysis
│
├── 📁 data
│   └── 📄 complaints_sample.csv              # Sample complaint data (single column: 'complaint_text')
├── 📁 notebooks
│   ├── ⚙️ .gitignore
│   └── 📄 01_nlp_complaints_analysis.ipynb   # Main analysis notebook with all code/results
├── 📁 results
│   └── 🌐 lda_topic_visualization.html       # pyLDAvis LDA topic visualization output 
├── 📝 README.md
├── 📄 requirements.txt                       # All required packages
└── ⚙️ .gitignore
```

---

## 🚀 Step-by-Step Setup & Execution

### 1. Clone the Repository and Position Yourself

```
git clone https://github.com/<your-username>/NLP-Complaints-Analysis.git
cd NLP-Complaints-Analysis
```

---

### 2. (Recommended) Create a Python Virtual Environment

- **Windows:**

python -m venv venv
venv\Scripts\activate


- **Mac/Linux:**

python3 -m venv venv
source venv/bin/activate

---

### 3. Install Required Dependencies

pip install -r requirements.txt

---

### 4. Install and Verify spaCy and English Model

- Make sure spaCy is installed:

```
pip install spacy
pip show spacy # Verify installation
```

- Download the English language model:

```
python -m spacy download en_core_web_sm
```

---

### 5. Confirm the Kernel/Interpreter in Virtual Studio Code

- Open VS Code in your project folder.
- Open the notebook located at `notebooks/01_nlp_complaints_analysis.ipynb`.
- Make sure the top-right kernel/interpreter matches the Python from your `venv` folder
(`<your-project-folder>/venv/Scripts/python.exe` on Windows, or `venv/bin/python` on Mac/Linux).

---

### 6. Run the Jupyter Notebook

- Either start Jupyter with jupyter notebook, and open in your browser,

- Or use the built-in Jupyter Notebook interface in VS Code (`.ipynb` file).

- **Run all cells** sequentially to process data, perform NLP, and generate results.

---

## 📊 Results and Output

- Interactive LDA topic model visualization is generated and saved to:

```
results/lda_topic_visualization.html
```

- Open this file in any web browser to explore identified topics and their salient terms.

---

## 📄 Files Delivered for Assessment

- `notebooks/01_nlp_complaints_analysis.ipynb` — Jupyter Notebook with all code, outputs, and markdown explanations.

- `data/complaints_sample.csv` — Sample dataset.

- `results/lda_topic_visualization.html` — Interactive visualization for academic inspection.

---

## ℹ️ Additional Notes

- Modify `data/complaints_sample.csv` to use your own municipal complaint data as needed.
- For reproducibility, all dependencies are listed in `requirements.txt`.
- If you experience environment/interpreter issues in Jupyter, ensure you re-select the correct `venv` in the notebook kernel picker, as described above.

---

## 📬 Contact

For questions or troubleshooting, contact [your-email@domain.com] or raise an issue in the repository.

---

**This README and repository are fully ready and compliant with university data analysis portfolio standards.**

---