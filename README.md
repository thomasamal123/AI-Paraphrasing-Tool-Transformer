# AI-Powered Paraphrasing Tool

##  Overview

This project presents an AI-powered paraphrasing system developed using transformer-based deep learning models. The tool takes input text and generates a paraphrased version while preserving meaning and ensuring grammatical correctness.

The system is implemented in Python using the Hugging Face Transformers library and includes additional features such as grammar checking and semantic similarity evaluation.

---

##  Objectives

- Generate paraphrased text using a transformer model
- Preserve semantic meaning while improving clarity
- Detect and correct grammar and spelling errors
- Evaluate output quality using semantic similarity

---

##  Technologies Used

- Python
- Hugging Face Transformers
- FLAN-T5 (Transformer Model)
- LanguageTool (Grammar Checking)
- Scikit-learn (Semantic Similarity using TF-IDF)

---

##  Model Used

The project uses **FLAN-T5 small**, an instruction-tuned transformer model.

### Why FLAN-T5?
- Efficient and lightweight
- Works well with instruction-based prompts
- Suitable for paraphrasing tasks
- Easy to integrate using Hugging Face

---

##  Features

- Paraphrasing using transformer model
- Grammar and spelling correction
- Console-based user input
- Multiple test cases
- Semantic similarity evaluation
- Handles both correct and incorrect input sentences

---

## Evaluation

Semantic similarity is used to evaluate how well the meaning is preserved.

### Example Results

| Case | Description | Similarity Score |
|------|------------|-----------------|
| Case 1 | Simplified output (loss of detail) | 0.2061 |
| Case 2 | Strong paraphrase | 0.8037 |
| Case 3 | Sentence simplification | 0.7579 |

---

##  Sample Output

**Input:**  
The restaurant serves delicious food, but the service can sometimes be slow.

**Paraphrased:**  
The food is delicious, but the service can sometimes be slow.

---

##  Challenges Faced

- Limited paraphrasing variation from small models
- Dependency conflicts between libraries
- Kernel crashes due to memory usage
- Evaluation metric inconsistencies

---

##  Key Learnings

- Understanding transformer-based NLP models
- Handling real-world implementation challenges
- Balancing simplicity, performance, and accuracy
- Evaluating NLP outputs effectively

---

##  How to Run

1. Open the Jupyter Notebook
2. Install required libraries:
3. 3. Run all cells step-by-step
4. Use the console input section to test custom sentences

---

##  Conclusion

This project demonstrates the practical application of transformer-based models in paraphrasing tasks. While the model performs well in preserving meaning, it also highlights limitations such as reduced variation and occasional simplification of input text.

---

##  Author

Developed as part of a Machine Learning / NLP module project.
