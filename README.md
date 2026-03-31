# AI-DDR-Report-Generator
AI system that converts inspection and thermal reports into a structured Detailed Diagnostic Report (DDR) using rule-based logic.

# 🧠 AI DDR Report Generator

## 📌 Overview

This project presents an AI-based workflow that converts raw **Inspection Reports** and **Thermal Reports** into a structured **Detailed Diagnostic Report (DDR)**.

The system extracts unstructured data from PDF documents and applies rule-based logic to identify key issues such as dampness, leakage, and structural defects. It then organizes the findings into a clear, client-friendly report format.

---

## 🎯 Objective

To design an intelligent system that:

* Extracts relevant observations from inspection and thermal reports
* Combines information logically
* Avoids duplicate findings
* Handles missing or unclear data
* Generates a structured DDR report

---

## ⚙️ How It Works

### 1. Data Extraction

* Reads PDF files using Python
* Extracts textual content from inspection and thermal reports

### 2. Data Processing

* Identifies keywords like *dampness, cracks, leakage, plumbing issues*
* Maps issues to specific areas (Hall, Bedroom, Kitchen, etc.)

### 3. Report Generation

* Generates a structured DDR report including:

  * Property Issue Summary
  * Area-wise Observations
  * Root Cause Analysis
  * Severity Assessment
  * Recommended Actions
  * Missing Information

---

## 🛠️ Tech Stack

* Python
* Google Colab
* PyPDF2

---

## 📂 Project Structure

```
AI-DDR-Report-Generator/
│
├── AI_DDR_Report_Generator.ipynb
├── DDR_Report.pdf
└── README.md
```

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Upload:

   * Inspection Report PDF
   * Thermal Report PDF
3. Run all cells
4. The system will generate the DDR output automatically

---

## 📊 Sample Output

The system generates a structured report with:

* Clear issue summary
* Area-wise breakdown
* Root cause identification
* Severity classification
* Actionable recommendations

---

## ⚠️ Limitations

* Rule-based approach (depends on keywords)
* Limited understanding of complex language variations
* Image mapping not implemented

---

## 🚀 Future Improvements

* Integration with NLP/LLM models for better understanding
* Automatic mapping of thermal images to observations
* Enhanced severity scoring system
* Support for multiple report formats

---

## 🎥 Demo

A demonstration video explaining the workflow and output is included in the submission.

---

## 📌 Conclusion

This project demonstrates how AI workflows can be designed to transform unstructured inspection data into meaningful, structured reports. It highlights practical problem-solving using simple and effective techniques.

---
