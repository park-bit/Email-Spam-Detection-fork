# 📧 Email Spam Detection (Forked & Improved)

A refactored and enhanced version of the original [kanagalingamcse/email-spam-detection](https://github.com/kanagalingamcse/email-spam-detection) project—improved preprocessing, clarified outputs, and added vectorizer/model export.

---------------------------------------------------------------------------------------

## 🔍 Features & Enhancements

- ✅ Improved text preprocessing (optimized stop-word filtering)
- 🧠 Three ML models:
  - Multinomial Naive Bayes (best performer)
  - Random Forest & Decision Tree
- 📊 Plots: Confusion matrices with labelled axes
- 💾 Exports:
  - `MNB.pkl`, `RFC.pkl`, `DTC.pkl` (trained models)
  - `vectorizer.pkl` (CountVectorizer)
- 💬 Custom test message at end of script to demo predictions

-------------------------------------------------------------------------------------------

## 🗂️ File Overview

| File | Description |
|------|-------------|
| `email_spam_detection.ipynb` | Jupyter Notebook with full workflow |
| `email_spam_detection.py`    | Script version for local execution |
| `MNB.pkl`, `RFC.pkl`, `DTC.pkl` | Serialized ML models |
| `vectorizer.pkl`             | Serialized feature vectorizer |
| `requirements.txt`           | Python dependencies |

You only need to modify the `.ipynb` or `.py` to update preprocessing, models, or add new tests. All other files are ready to use.

---

## ⚙️ How to Use It

1. Clone this updated repo:
   git clone https://github.com/park-bit/Email-Spam-Detection-fork.git
   cd Email-Spam-Detection-fork
   
2. Install the dependencies:
   pip install -r requirements.txt

3. Run training and saving models:
   python email_spam_detection.py

4. Test a custom message:

Edit the test_message = [...] variable at the end of email_spam_detection.py, run the script, and get your prediction!

-------------------------------------------------------------------------------------
Credits
This project is based on the original work by kanagalingamcse. Enhancements and exports added in this fork by me :)


--------------------------------------------------------------------------------------

### 🧾 Summary
- You don’t need to modify any other file.
- Update your `README.md` with the above snippet, commit and push.
- If you'd like deployment (Flask/Streamlit) next, I can help with that.

Let me know!
::contentReference[oaicite:0]{index=0}
