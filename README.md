# warmup
Setting up the prediction model

# libraries
`pip install transformers`
`pip install torch torchvision`
`pip install transformers datasets torch scikit-learn`
`pip install transformers[torch]`

# key features of the code
-Uses the IMDb dataset for binary sentiment classification (positive vs. negative).
-Tokenizes the input text, truncating or padding to a fixed length (max_length=128).
-Fine-tunes the bert-base-uncased model on the IMDb dataset using the Hugging Face Trainer API.
-Saves the fine-tuned model and tokenizer locally in ./my_local_model so it can be reused without internet access.
-Demonstrates how to load the locally saved model and use it for prediction

Class 0: Negative Sentiment
Class 1: Positive Sentiment