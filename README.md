# FOSSEE Task 3: Student Competence Analysis

## Overview
This project evaluates open-source AI models for analyzing Python code written by students and generating prompts to assess their competence. The main goal is to identify gaps in reasoning, highlight misconceptions, and encourage deeper understanding without providing direct solutions.

The evaluation focuses on **CodeBERT**, a model designed for code understanding and generation. The Python code snippets used as a **dataset** are stored in the `examples/` folder.

---

## Research Plan

**Approach to Identifying and Evaluating Models:**  
I chose **CodeBERT**, an open-source model optimized for understanding code. Its ability to parse Python syntax and analyze code structure makes it suitable for competence assessment. The evaluation involves feeding Python code snippets from the `examples/` folder into CodeBERT, checking whether it can identify errors, suggest improvements, and generate prompts that encourage conceptual understanding. Key evaluation criteria include **accuracy, interpretability, clarity, and practicality**.

**Testing and Validation:**  
The model will be tested on snippets covering loops, functions, data structures, and recursion. The aim is to verify whether the model can:  
- Identify coding errors or gaps in reasoning  
- Generate meaningful prompts for students  
- Encourage deeper learning without giving away answers  

**Trade-offs:** While CodeBERT is strong in code comprehension, it may struggle with highly complex or ambiguous code. We balance **accuracy, interpretability, and computational cost** in evaluation.

---

## Reasoning

- **Model suitability:** CodeBERT can parse Python code and generate useful feedback for competence analysis.  
- **Testing prompts:** I will check that prompts guide students toward understanding rather than providing direct answers.  
- **Trade-offs:** Balancing accuracy, interpretability, and computational resources is key.  
- **Choice justification:** CodeBERT is open-source, accessible, and focused on code-related tasks, making it a strong candidate. Limitations are manageable with proper test examples.

---

## Folder Structure

FOSSEE Task 3: Student Competence Analysis/
│

├── README.md # This file

├── examples/ # Dataset of Python code snippets

│ ├── example1.py

│ ├── example2.py

│ ├── example3.py

│ └── example4.py

├── evaluate_model.py # Script to demonstrate evaluation

└── requirements.txt # Dependencies


**Note:** The `examples/` folder serves as the dataset for evaluation.

---

## Setup Instructions

1. Install Python 3.10+  
2. Install required libraries:
pip install -r requirements.txt
3. Run the evaluation script:
python evaluate_model.py

References

CodeBERT on Hugging Face

Author: Chebrolu Chaithanaya Kumar

Email: chaithanyakumar.616@gmail.com

GitHub: https://github.com/2300033094
