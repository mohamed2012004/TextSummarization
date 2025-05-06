# Text Summarization with Hugging Face

## Overview
This project demonstrates fine-tuning a pre-trained Hugging Face model (Google Pegasus CNN Daily Mail) for text summarization using the Samsung dataset.

## Steps:

1. **Setup Environment**
      - Install required libraries (transformers, datasets, rouge_score, evaluate)

2. **Load Model & Data**
   - Load pre-trained Pegasus model and tokenizer
   - Download and prepare Samsung dataset (dialogue-summary pairs)

3. **Data Preparation**
   - Convert text to tokens using the model's tokenizer
   - Prepare input_ids, attention_mask, and labels for sequence-to-sequence training

4. **Fine-Tuning**
   - Configure training arguments (epochs, batch size, etc.)
   - Initialize trainer with model, tokenizer, and datasets
   - Run training process

5. **Evaluation**
   - Calculate ROUGE scores (ROUGE-1, ROUGE-2, ROUGE-L)
   - Compare generated summaries with reference summaries

6. **Inference**
   - Save fine-tuned model and tokenizer
   - Create a pipeline for generating summaries from new dialogues

## Results
The model can generate concise summaries from dialogue text, with performance dependent on training duration and dataset quality.

### Project Workflow 
1. Config.yaml
2. Params.yaml
3. Config entity
4. Configuration Manager
5. Update the components- Data Ingestion,Data Transformation, Model Trainer
6. Create our Pipeline-- Training Pipeline,Prediction Pipeline
7. Front end-- Api's, Training APi's, Batch Prtediction API's

Try it yourself
[Google Colab Notebook](https://colab.research.google.com/drive/1HBn8UEVvxOFJ4GydQBM_r2bgLZFWPLOL?usp=sharing)



https://github.com/user-attachments/assets/6ef630be-3694-4472-bb3c-0694eaa37067
