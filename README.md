# Drug_Drug_Interaction
This is the final project for Unsupervised Learning and Data Analysis. The goal of this project is to detect any potential drug drug interation by reading drug labels. This peoject rely heavily on Natural language processing. The project is wriiten in python.

A method proposed, by extracting information from drug labels (active ingredient, active moiety, indication and usage, contraindication, and adverse reactions), the drug’s information is embedded to a unique 5*768 matrix and fed as inputs for prediction. 

A total of four sentence-embedding methods - one self-trained called PharmBert together with three other language models, all based on bidirectional encoder representations from transformers (BERT) are applied and tested. 

The prediction is not very accurate but PharmBert works better than all other language models does suggesting the embedding works to some extent and the drug pair who have interactions is different than those who do not by analyzing through the embedded space.

The detailed report can be accessed in this git repository: Representation_Learning_On_Drug_Labels_for_Predicting_Drug_Drug_Interaction__DDI__1.pdf
