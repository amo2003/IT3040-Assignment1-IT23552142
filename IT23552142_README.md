# IT3040 – Assignment 1 (Option 1)

## Transliteration Accuracy Testing using Playwright

### 👨‍🎓 Student Information

* **Name:** M.M.A. Indupa
* **Registration Number:** IT23552142
* **Module:** IT3040 – ITPM
* **Year/Semester:** Year 3 – Semester 1

---

## 📌 Project Overview

This project evaluates the accuracy of the **Chat Sinhala Transliteration** feature available at:
👉 https://www.pixelssuite.com/chat-translator

The main objective is to identify cases where **chat-style Singlish input is incorrectly converted into Sinhala output**.

---

## 🎯 Objectives

* Test transliteration accuracy using real-world Singlish inputs
* Identify **50 failed test cases**
* Automate testing using **Playwright**
* Generate execution results into an **Excel file**

---

## 🛠️ Technologies Used

* Python 3.x
* Playwright
* OpenPyXL
* Excel (for result tracking)

---

## 📂 Project Structure

```
IT3040-Assignment1-IT23552142/
│
├── test_automation/
├── Assignment 1 - Test cases.xlsx   # Test cases & results
├── README.md
└── requirements.txt
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/amo2003/IT3040-Assignment1-IT23552142.git
cd IT3040-Assignment1-IT23552142
```

---

### 2️⃣ Install Dependencies

```bash
pip install -U pip
pip install playwright openpyxl
```

---

### 3️⃣ Install Playwright Browsers

```bash
playwright install
```

---

## ▶️ Running the Automation Script

```bash
python test_automation/test_script.py
```

---

## 📊 Test Case Details

* Total Test Cases: **50**
* Each test case includes:

  * Singlish Input
  * Expected Sinhala Output
  * Actual Output
  * Pass/Fail Status

✔ All test cases focus **only on Chat Transliteration**
❌ Standard Sinhala, API testing, and performance testing are excluded

---

## 📁 Output

The execution results are saved in:

```
Assignment 1 - Test cases.xlsx
```

This file includes:

* Automated execution results
* Pass/Fail evaluation
* Identified system weaknesses

---

## 🧪 Test Coverage

* Minimum **2 test cases per Singlish input type**
* Covers:

  * Informal typing styles
  * Slang variations
  * Mixed language inputs
  * Common typing mistakes

---

**End of README**
