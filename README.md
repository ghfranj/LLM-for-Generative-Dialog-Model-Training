# LLM-for-Generative-Dialog-Model-Training

_____

# Link to the notebook
# Generative Dialog Model Training
https://colab.research.google.com/drive/1R_TlBbA13Y_XXJ0gmLQSTwcPA4KX6MvR?usp=sharing


This notebook contains code and resources for training a generative dialog model with context accumulation. The model architecture can utilize is an encoder-decoder backbone. It is trained on a dialog dataset in Russian language to generate responses in conversations. The dialog cycle is implemented to accumulate context history during the conversation. Parameters for response generation are fine-tuned, and the quality of responses is evaluated using text-based metrics.

## Dataset
The dataset used for this task providing dialog data in Russian:
- [TlkPersonaChatRus](https://tlk.s3.yandex.net/dataset/TlkPersonaChatRus.zip)
  
## Requirements
- Python 3
- PyTorch
- Transformers library
  
## Usage
1. **Data Preparation**.
2. **Model Training**.
3. **Dialog Generation**.
4. **Evaluation**.
## Results
- Evaluation results, including metrics such as BLEU score are used.
