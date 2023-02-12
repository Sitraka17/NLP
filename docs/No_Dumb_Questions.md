# Basics_NLP_101

To form yourself really easily: [TF tutorial](https://www.tensorflow.org/tutorials?hl=fr)


**Cosine similarity** is a measure of similarity between two non-zero vectors defined in an inner product space



# BERT 
What is **768** in BERT ?
The BERTBase model uses #12 layers# of transformers block with a hidden size of 768 and number of self-attention heads as 12 and has around 110M trainable parameters


*What is a Transformer?*
NLP's Transformer is a new architecture that aims to solve tasks sequence-to-sequence while easily handling long-distance dependencies. Computing the input and output representations without using sequence-aligned RNNs or convolutions and it relies entirely on self-attention

Pre_Trained ? 
Yeah that's why we call/summon them juste like this: 
> bert_preprocess = hub.KerasLayer("https://tfhub.dev/tensorflow/bert_en_uncased_preprocess/3")
> bert_encoder = hub.KerasLayer("https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12/4") 


# Elmo
ELMo is a novel way to represent words in vectors or embeddings. These word embeddings are helpful in achieving state-of-the-art (SOTA) results in several NLP tasks: NLP scientists globally have started using ELMo for various NLP tasks, both in research as well as the industry.
