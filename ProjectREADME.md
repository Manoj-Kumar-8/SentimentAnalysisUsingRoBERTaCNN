
# 🧠 RoBERTaCNN (Jupyter Notebook Version)

This project implements a hybrid text classification model that combines **RoBERTa** for contextual embeddings with a **CNN layer** to capture local n-gram patterns. The entire pipeline — from preprocessing to evaluation — is contained within a single Jupyter Notebook.

---

## 📄 File

- `SentimentAnalysisUsingRoBERTaCNN.ipynb`: Complete model code including:
  - Data loading
  - Tokenization using Hugging Face Transformers
  - RoBERTa embedding extraction
  - CNN layer for classification
  - Training loop
  - Evaluation metrics

---

## 📌 Requirements

Make sure you have the following Python libraries installed:

```
transformers
torch
sklearn
pandas
numpy
matplotlib
```

Install them using:

```bash
pip install transformers torch scikit-learn pandas numpy matplotlib
```

---

## 🚀 How to Run

1. Open Jupyter Notebook or Jupyter Lab.
2. Launch the notebook:
   ```
   jupyter notebook RoBERTaCNN.ipynb
   ```
3. Run the cells in order to train and evaluate the model.

---

## 📊 Output Example

| Metric   | Value   |
|----------|---------|
| Accuracy | 93.1%   |
| F1 Score | 93.0%   |

> Replace this with your actual results after training.

---

## 📚 References

- [RoBERTa Paper](https://arxiv.org/abs/1907.11692)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [CNN for Sentence Classification](https://arxiv.org/abs/1408.5882)

---

## 👤 Author

**Jampala Manoj Kumar**  
📧 Email: manojkumarjampala23@example.com  
🔗 LinkedIn: [linkedin.com/in/manoj-kumar-jampala](www.linkedin.com/in/manoj-kumar-jampala-3261562a6)

---

## 📄 License

This project is licensed under the MIT License.
