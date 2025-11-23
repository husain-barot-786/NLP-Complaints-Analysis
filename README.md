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
│   └── 📄 01_nlp_complaints_analysis.ipynb   # Main analysis notebook with all code/results
├── 📁 results
│   └── 🌐 lda_topic_visualization.html       # pyLDAvis LDA topic visualization output
├── 📁 result_screenshots
│   ├── 🖼️ Figure_1_LDA_Topic_Distance_Map.png
│   ├── 🖼️ Figure_2_LDA_Topic_1_Terms.png
│   └── 🖼️ Figure_3_LDA_Topic_2_Terms.png
├── 📝 README.md
├── 📄 requirements.txt                       # All required packages
└── ⚙️ .gitignore
```

---

## 🚀 Step-by-Step Setup & Execution

### 1. Clone the Repository and Position Yourself

```
git clone https://github.com/husain-barot-786/NLP-Complaints-Analysis
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
pip show spacy        # Verify installation
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
(`NLP-Complaints-Analysis/venv/Scripts/python.exe` on Windows, or `venv/bin/python` on Mac/Linux).

---

### 6. Run the Jupyter Notebook

- Start Jupyter with `jupyter notebook`or use VS Code’s built-in notebook support.

- **Run all cells** sequentially to process data, perform NLP, and generate results.

---

## 📊 Results and Output

- Interactive LDA topic model visualization is generated and saved to:

```
results/lda_topic_visualization.html
```

- Open this file in any web browser to explore identified topics and their salient terms.

- **Screenshots of key result views** have been provided for easy reference:

- `result_screenshots/Figure_1_LDA_Topic_Distance_Map.png`: Intertopic Distance Map and overview of topics
- `result_screenshots/Figure_2_LDA_Topic_1_Terms.png`: Top relevant terms for Topic 1
- `result_screenshots/Figure_3_LDA_Topic_2_Terms.png`: Top relevant terms for Topic 2

---

## 📄 Files Delivered for Assessment

- `notebooks/01_nlp_complaints_analysis.ipynb` — Jupyter Notebook with all code, outputs, and markdown explanations.

- `data/complaints_sample.csv` — Sample dataset of municipal complaints.

- `results/lda_topic_visualization.html` — Interactive LDA visualization for academic inspection.

- `result_screenshots/` — Key result images for rapid assessment and documentation.

---

## ℹ️ Additional Notes

- Modify `data/complaints_sample.csv` to use your own municipal complaint data as needed.
- If you experience environment/interpreter issues in Jupyter, ensure you re-select the correct `venv` in the notebook kernel picker, as described above.
- Datasets and screenshots included are for demonstration; replace or expand with your real municipal data as needed.
- All dependencies are listed in `requirements.txt` for full reproducibility.
- If Jupyter gives environment errors, confirm you’re using the correct venv in the notebook kernel picker.

---

## 📬 Contact

For questions or troubleshooting, contact `husain7083078653@gmail.com` or raise an issue in the repository.

---