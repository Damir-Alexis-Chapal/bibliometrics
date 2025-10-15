# Bibliometric Analysis Project

## 🧠 Overview
This is a university project aimed at developing a bibliometric analysis and visualization tool similar to **VOSviewer**.  
The goal is to analyze scientific publication data, extract relationships between authors, keywords, or institutions, and visualize them as interactive networks.

---

## ⚙️ Environment Setup (Windows 10/11)

### 1️⃣ Uninstall Python 3.14
If you had Python 3.14 installed, uninstall it first:

1. Open **Control Panel → Programs and Features**.
2. Locate **Python 3.14** and click **Uninstall**.
3. (Optional) Delete any leftover folder:


---

### 2️⃣ Install Python 3.12
Download and install **Python 3.12 (64-bit)** from:
👉 [https://www.python.org/downloads/release/python-3126/](https://www.python.org/downloads/release/python-3126/)

During installation:
- ✅ Check **Add Python to PATH**
- ✅ Select **Customize installation**
- Make sure the following options are enabled:
- `pip`
- `venv`
- *(optional)* Install for all users

---

### 3️⃣ Verify Installation
Open **PowerShell** or **CMD** and run:

```bash
python --version
pip --version
```
Expected output:
```bash
  Python 3.12.6
  pip 24.2
```
---

### 4️⃣ Create a Virtual Environment
  In your project directory:
  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```
Once activated, your terminal should display (venv) before the path.

---

### 5️⃣ Install Required Libraries
With the virtual environment active, install the core dependencies:
  ```bash
  pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud
  ```
These packages are used for:

- Data analysis: pandas, numpy
- Visualization: matplotlib, seaborn, wordcloud
- Text mining and NLP: nltk, scikit-learn

---
👨‍💻 Author

Developed by Damir Alexis Chapal

University Project — 2025

---
