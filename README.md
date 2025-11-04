# Data Mining Methodologies — CMPE 255 Assignment

**Author:** Shreram Palanisamy  
**Course:** CMPE 255  Data Mining

> Three compact, end-to-end Colab projects demonstrating **CRISP-DM**, **KDD**, and **SEMMA** on small tabular datasets. The focus is on **clear methodology**, **leak-safe pipelines**, and **reproducible results**.

---

### 🤖 AI Assistance Disclosure

This project used **ChatGPT (GPT-5 Thinking)** to help structure and critique each stage of the three methodologies (**CRISP-DM**, **KDD**, **SEMMA**).  
ChatGPT acted as a “domain expert reviewer,” suggesting refinements to phase plans, code modularity, and evaluation clarity.  
All generated code and analyses were **verified, executed, and finalized manually** by **Shreram Palanisamy** before inclusion.  
Curated chat transcripts are stored in the [`ai_reviews/`](./ai_reviews) directory for reference.

---


## 📚 Methods Covered

- **CRISP-DM:** Business Understanding → Data Understanding → Data Preparation → Modeling → Evaluation → Deployment  
- **KDD:** Selection → Preprocessing → Transformation → Data Mining → Interpretation/Evaluation  
- **SEMMA:** Sample → Explore → Modify → Model → Assess  

---

Each notebook is self-contained and designed to run in **Google Colab**.

---

## 🧪 Notebooks

| Method | Notebook | Open in Colab |
|---|---|---|
| **CRISP-DM** | [`CRISP-DM..ipynb`](./CRISP-DM..ipynb) | <https://colab.research.google.com/github/shreramsp/data-mining-methodologies---CMPE-255-Assignment/blob/main/CRISP-DM..ipynb> |
| **KDD** | [`KDD.ipynb`](./KDD.ipynb) | <https://colab.research.google.com/github/shreramsp/data-mining-methodologies---CMPE-255-Assignment/blob/main/KDD.ipynb> |
| **SEMMA** | [`SEMMA.ipynb`](./SEMMA.ipynb) | <https://colab.research.google.com/github/shreramsp/data-mining-methodologies---CMPE-255-Assignment/blob/main/SEMMA.ipynb> |

---

## 📊 Datasets & Sources

### CRISP-DM — Adult / Census Income
- **Task:** Binary classification (`>50K` vs `<=50K`)
- **Sources:**
  - Kaggle — <https://www.kaggle.com/datasets/uciml/adult-census-income>

### KDD — Breast Cancer Wisconsin (Diagnostic)
- **Task:** Binary classification (Malignant vs Benign)
- **Source:**
  - Kaggle - <https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data>

### SEMMA — Pima Indians Diabetes
- **Task:** Binary classification (`Outcome`: 1 = diabetes, 0 = no diabetes)
- **Source:**
  - Kaggle — <https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database>

---

## 🎥 YouTube Walkthroughs

- **CRISP-DM:** <https://youtu.be/ARmOUjRLCxA>
- **KDD:** <https://youtu.be/tWn9nqTSAmo>
- **SEMMA:** <https://youtu.be/Jl6lLHbh7rc>

--

## ✍️ Medium Articles

- **CRISP-DM:** <https://medium.com/@shrerampalanisamy/from-chat-to-classification-predicting-adult-income-with-chatgpt-crisp-dm-cost-aware-ml-d4fa733b63c9>  
- **KDD:** <https://medium.com/@shrerampalanisamy/from-chat-to-classification-a-kdd-mini-demo-on-breast-cancer-wdbc-e2f47c524114>  
- **SEMMA:** <https://medium.com/@shrerampalanisamy/from-chat-to-classification-predicting-diabetes-with-chatgpt-semma-compact-ml-58d6a4f7e182>

Each article provides a short narrative, key decisions, and artifact screenshots.

---

## ▶️ How to Run (Colab)

1. Open a notebook using the **Open in Colab** link above.  
2. **Mount Google Drive** if the notebook references `/content/drive/...`.  
3. Ensure the dataset path matches your Drive location (or use the provided download cell, if present).  
4. Run the cells **top-to-bottom**.

---

## ⚙️ Environment

- **Python:** 3.x (Colab default)  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`

---

## 🔁 Reproducibility Practices

- Fixed seeds (`random_state=42`)  
- **Stratified** train/validation/test splits (where applicable)  
- All preprocessing inside **`Pipeline`/`ColumnTransformer`**, **fit on train only**  
- Lightweight evaluation (no heavy hyperparameter sweeps), compact plots

---

## 📝 Notes

These notebooks are **educational mini-demos** that emphasize methodology clarity and good ML hygiene (leak-safe prep, simple baselines, concise evaluation). For extended write-ups and results, see the Medium articles linked above.

---

## 🙌 Acknowledgments & License

 
- **License(MIT):** free to use for educational and research purposes.



