# T5-Base-Mode-Fine-Tuned-For-Title-Generation

The T5-Base model was fine-tuned for the task of title generation from text bodies. Additionally, an experimental fine-tuning was conducted to enable the model to generate titles based on references, using data scraped from Wikipedia as the training and testing corpus.

For the primary task of generating titles from body text, the fine-tuned model achieved a ROUGE-1 score of 0.85 and a ROUGE-L score of 0.87, indicating strong alignment with human-generated titles.

To facilitate easy interaction with the model, a Flask API was developed and thoroughly tested using Postman, ensuring robust performance and reliability.
