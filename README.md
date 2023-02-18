# Document-Similarity-Finding-using-BERT
Recently, there has been growing interest in the ability of Transformer based models to produce meaningful embeddings of text with several applications, such as text similarity. Despite significant progress in the field, the explanations for similarity predictions remain challenging, especially in unsupervised settings.
       In this work, we present  an unsupervised technique  for  explaining  paragraph  similarities  inferred  by
pre-trained BERT models. 

## BERT Documentation

We used a  language representation model called BERT, which stands for Bidirectional Encoder Representations from Transformers. BERT is designed to pretrain deep bidirectional representations from unlabeled text by jointly conditioning on both left and right context in all layers. As a result, the pre-trained BERT model can be finetuned with just one additional output layer to create state-of-the-art models for a wide range of tasks, such as question answering and language inference, without substantial taskspecific architecture modifications.

>BERT is a special  minimum viable product of Natural Language Processing.


![Bert is deeply  bidirectional](https://user-images.githubusercontent.com/92162301/219870671-e152cc53-29ea-45db-9311-1171bb918322.png)

## Methodology
- ### Approach 1
    - In this approach, we have just the sentences as inputs to the model , the model encodes it and find the similarity percentage.
- ### Approach 2
    - In this approach, we have first tokenized the sentences and then passed the tokens to the model. 
    - By doing so it helps in increasing the accuuracy of the model.

- ## Heat Map
    - For creating Heat Map,we have broken down paragraph into sentences,to look sentences-to-sentences semantic similarity. 
    
    
