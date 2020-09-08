# NLP

I have used Google colab for this task due to its availability of free GPUs and TPUs. 
Training models, especially deep learning ones, takes numerous hours on a CPU. We’ve all faced this issue on our local machines. GPUs and TPUs, on the other hand, can train these models in a matter of minutes or seconds.

Hugging Face has collection of Transformer classes -- it also hosts a repository for pre-trained and fine-tuned models contributed from the wide community of NLP practitioners. 

IN this Question Answering task of NLP I have used one such pre-fine-tuned model (Fine-tuned BERT on SQuAD dataset)
Whether you fine-tuned your own or used a pre-fine-tuned model,there are three steps to QA:

1. tokenize the input
2. obtain model scores
3. get the answer span



