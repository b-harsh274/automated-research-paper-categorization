# 📄 Automated Research Paper Categorization

Automatically classify research paper titles and abstracts into one of **57 academic categories** using state-of-the-art NLP models.  
This project fine-tunes transformer architectures and uses an **ensemble** for improved accuracy, helping streamline category selection during the paper-submission process.

---

## 🚀 Overview

During research paper submissions, authors must manually pick relevant categories from a large list.  
This process is often time-consuming, inconsistent, and prone to error.

This project automates category recommendation by:

- taking **title + abstract** as input  
- using fine-tuned transformer models  
- predicting the **most relevant research fields**  
- improving accuracy through **model ensembling**

Designed for conferences, journals, indexing platforms, or any system requiring paper categorization.

---

## 🧠 Models Used

We experimented with and fine-tuned the following transformer-based models:

- **RoBERTa-base**  
- **DeBERTa-base**  
- **DeBERTa-large**

### 🔧 Ensemble Method
To maximize accuracy, predictions from all three models are combined via a weighted ensemble.

---

## 📊 Performance

- **Final Ensemble F1 Score:** **0.70**

This demonstrates strong performance across all 57 multi-class labels.

---

## 📁 Repository Contents

### Jupyter Notebooks Included
- `deberta.ipynb` – DeBERTa-base training  
- `deberta_overfit.ipynb` – Overfitting test notebook  
- `deberta_large.ipynb` – DeBERTa-large fine-tuning  
- `roberta.ipynb` – RoBERTa-base training  
- `inference.ipynb` – Final inference workflow  

(Adapted from the original group project.)

---

## 👤 Author

**Harsh Balgude**  
Email: [harshbalgude@gmail.com](mailto:harshbalgude@gmail.com)  
GitHub: [b-harsh274](https://github.com/b-harsh274)

---

## 🙏 Acknowledgements

Originally developed as part of a collaborative group project.  
Special thanks to:

- **Krishna Mahalka**  
- **Rahul Jat**

