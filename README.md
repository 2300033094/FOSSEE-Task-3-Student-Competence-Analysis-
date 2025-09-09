# Python Screening Task 3 – Research Plan

## Research Plan

**Approach to Identifying and Evaluating Models:**  
I plan to evaluate **CodeBERT**, an open-source model designed for understanding and generating code. I chose this model because it can analyze Python code and has shown strong capabilities in understanding code structure, which is essential for evaluating student competence. My approach involves using a set of Python code examples, feeding them into the model, and checking whether it can identify errors, gaps in reasoning, or areas for improvement. I will also assess whether the model can generate meaningful prompts that encourage deeper learning without giving away the solutions. The evaluation will consider accuracy, clarity, interpretability, and practicality.

**Testing and Validation:**  
I will test the model on Python snippets covering loops, functions, data structures, and recursion. The goal is to see if the model can highlight issues, suggest improvements, and produce prompts that guide conceptual understanding. I will consider trade-offs between accuracy, interpretability, and computational cost. CodeBERT’s strengths include its code comprehension and prompt generation abilities, while limitations may include handling highly complex or ambiguous code. This approach ensures a clear, evidence-based evaluation of its suitability for educational use.

## Reasoning
- **Model suitability:** CodeBERT can parse Python code and generate useful feedback for competence analysis.
- **Testing prompts:** I will check if prompts guide students toward understanding rather than providing direct answers.
- **Trade-offs:** Balancing prompt accuracy, interpretability, and computational resources is key.
- **Choice justification:** CodeBERT is open-source, accessible, and focused on code-related tasks, making it a strong candidate. Limitations can be managed with proper test examples.

## Setup Instructions
1. Make sure Python 3.10+ is installed.
2. Install required libraries:
```bash
pip install -r requirements.txt
```
3. Run the evaluation script to see how the model could analyze code examples:
```bash
python evaluate_model.py
```

## References
- [CodeBERT on Hugging Face](https://huggingface.co/microsoft/codebert-base)
