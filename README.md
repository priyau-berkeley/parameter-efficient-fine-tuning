**parameter efficient fine tuning (PEFT) using PyTorch and GPT2**
**Fine Tuning Notebook This notebook uses PyTorch and Open AI's early Open Source Model GPT2 to develop a deeper understanding and intuition of how language models are fine-tuned with parameter efficient fine tuning (PEFT) techniques. 
We will continue to look at a specific simple task, Sentiment Classification, and see how we can fine tune two different models to improve performance. 
**a. Fine-tuning of GPT2 large with a sentiment classification dataset** Explored how we can combine Low Rank Adaptation (LoRA) with Quantization to fine tune a larger model. 
**b. Fine-tuning of Gemma model for Sentiment Analysis** Used a larger more recent model -- Gemma 2 from Google -- to illustrate the benefits of an increase in the number of parameters and how it affects the performance of the model.
This model doubles the number or parameters but has also undergone a better pre-training regime and we would expect that to be reflected in the performance of the model.
