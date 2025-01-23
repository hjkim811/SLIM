## SLIM: Sentiment Lexicon Integrated Meta-training for Low-resource Sentiment Analysis
In this repository, we provide checkpoints of the meta-trained models developed using our SLIM framework.
SLIM models are optimized for sentiment classification and rating classification tasks in few-shot settings.
You can download the models via Hugging Face or Google Drive.

### Hugging Face
Use the following code to load one of the models listed below.
```python
from transformers import AutoTokenizer, AutoModelForSequenceClassification

tokenizer = AutoTokenizer.from_pretrained("hjkim811/SLIM-W_polar")
model = AutoModelForSequenceClassification.from_pretrained("hjkim811/SLIM-W_polar")
```
- `SLIM-C_boolean`: https://huggingface.co/hjkim811/SLIM-C_boolean
- `SLIM-C_mixed`: https://huggingface.co/hjkim811/SLIM-C_mixed
- `SLIM-C_polar`: https://huggingface.co/hjkim811/SLIM-C_polar
- `SLIM-W_boolean`: https://huggingface.co/hjkim811/SLIM-W_boolean
- `SLIM-W_mixed`: https://huggingface.co/hjkim811/SLIM-W_mixed
- `SLIM-W_polar`: https://huggingface.co/hjkim811/SLIM-W_polar

### Google Drive
- All models: https://bit.ly/slim_models

### Notes
- `SLIM-W_polar` is the best-performing model and is recommended for use.
- More details about the framework and the models will be available in our paper 'Sentiment Lexicon Integrated Meta-training for Low-resource Sentiment Analysis' (under review).
