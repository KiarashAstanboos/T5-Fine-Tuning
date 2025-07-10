This project shows how the T5-small transformer model was fine-tuned for a multi-class classification task. The goal is to predict the correct label from a given text input using a custom dataset.

##  Model

- **Base model**: [T5-small](https://huggingface.co/t5-small)
- **Framework**: PyTorch with HuggingFace Transformers
- **Training monitor**: Weights & Biases

## 📊 Results
The model was trained and evaluated with tracking via [Weights & Biases](https://wandb.ai/kiarash-astanboos-ferdowsi-university-of-mashhad/Neural%20Network%20LLM%20HW5/runs/lkc8xn5g).

###  Final Evaluation Metrics

| Metric      | Value |
|-------------|-------|
| Accuracy    | 0.983 |
| Precision   | 0.983 |
| Recall      | 0.983 |
| F1-Score    | 0.983 |
