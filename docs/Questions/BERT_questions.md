# BERT 
What is **768** in BERT ?
The BERTBase model uses #12 layers# of transformers block with a hidden size of 768 and number of self-attention heads as 12 and has around 110M trainable parameters


*What is a Transformer?*
NLP's Transformer is a new architecture that aims to solve tasks sequence-to-sequence while easily handling long-distance dependencies. Computing the input and output representations without using sequence-aligned RNNs or convolutions and it relies entirely on self-attention

Pre_Trained ? 
Yeah that's why we call/summon them juste like this: 
> bert_preprocess = hub.KerasLayer("https://tfhub.dev/tensorflow/bert_en_uncased_preprocess/3")
> bert_encoder = hub.KerasLayer("https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12/4") 

