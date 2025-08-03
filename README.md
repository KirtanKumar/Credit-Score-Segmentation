# Credit-Score-Segmentation
This project analyses and segments FICO credit scores from the LendingClub dataset into interpretable credit risk bands using statistical binning techniques. By applying both **uniform** (equal-width) and **quantile** (equal-frequency) strategies via `KBinsDiscretizer`, we transform continuous credit scores into five distinct risk levels.

---

## 📁 Dataset

- **Source**: [Loan Data (Kaggle)](https://www.kaggle.com/datasets/kirtankumar/fico-score)
- **File Used**: `Task 3 and 4_Loan_Data.csv`

---

## ⚙️ Methodology

1. Load and preprocess the dataset
2. Extract a representative FICO score from available columns
3. Handle missing or infinite values
4. Apply binning using:
   - `uniform` strategy (equal score intervals)
   - `quantile` strategy (equal number of records)
5. Label risk bands:  
   **Very Low**, **Low**, **Medium**, **High**, **Very High**
6. Visualise:
   - FICO score distribution
   - Comparison of binning methods

---

## 📦 Tech Stack

- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---

## 🌐 View the Notebook on Kaggle

You can explore the full notebook and code on Kaggle:

🔗 [View on Kaggle](https://www.kaggle.com/code/kirtankumar/credit-score-segmentation)

Feel free to upvote, comment, or suggest improvements!

## 📌 Output

- Preview of risk-labelled FICO scores
- Histogram of FICO score distribution

---

## 📈 Example Columns After Binning

| FICO_Score | Risk_Band_Uniform | Risk_Label_Uniform | Risk_Band_Quantile | Risk_Label_Quantile |
|------------|-------------------|---------------------|---------------------|----------------------|
| 710        | 3                 | High                | 2                   | Medium               |

---

## 📄 License

This project is for academic and educational purposes only.

---

## 🙋‍♂️ Author

Kirtan Kumar  
NIT Rourkela
