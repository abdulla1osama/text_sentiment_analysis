# Text Sentiment Analysis using BERT (Transformers)
The following porject uses BERT to classify text sentiment whether negative or positive. The model is trained on IMDB dataset reviews with equally distributed negative and positive sentiment values.

🚀 Key Features
BERT-Powered Intelligence: Uses Google’s BERT model to understand the actual meaning of reviews, not just keywords.

Smart Tokenization: Uses sub-word splitting so the model never gets confused by "unknown" words or typos.

Hugging Face Integration: Built with the industry-standard transformers library for fast and easy model loading.

GPU Optimized: Designed to run on Google Colab/Kaggle GPUs for high-speed training (3-4 epochs in minutes).

Ready-to-Use Inference: Includes a simple function where you can paste any review and get an instant "Positive" or "Negative" result.

🛠️ Getting Started
To run this project, you don't need to install anything on your local machine. We use Google Colab to access free GPU power.

1. Open the Notebook
Click the BERT_Sentiment_Analysis.ipynb file in this repository.

Click the "Open in Colab" badge at the top.

2. Enable GPU (Critical)
BERT is a heavy model and requires a GPU to train.

In Colab, go to: Runtime > Change runtime type.

Select T4 GPU (or any available GPU) and click Save.

3. Install Dependencies
Run the first cell in the notebook to install the necessary Hugging Face libraries:

Bash

pip install transformers datasets torch
