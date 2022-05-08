# Assignment_3

This Repository contains the 4 files they are: Best_model_with_attention.ipynb, Best_model_without_attention.ipynb, Seq2Seq_with_attention.ipynb, rnn_seq_to_seq.ipynb  

File Name:rnn_seq_to_seq.ipynb  
File Description: This file contains the wandb sweep configuration for RNN based seq2seq model to generate data translations from english to tamil  
By changing sweep config we can select the parameters values to experiment. 

Important Functions:
**data_preprocessing:**	Preprocess the dataset and pads the output and also responsible for Tokenizing.   
**seq_seq_model:**	    This function creats and returns the model.  
**inference_:**         This function performs the inference process to decode the given input.  
**decode_and_eval:**	  This function wil decode the inputs and also returns the val accuracy or Test accuracy based on the **test_f** flag value. If test_f is False this function will return val accuracy other wise it will return the test accuracy and creates the correct_preds.txt and wrong_preds.txt.  

File Name:Best_model_without_attention.ipynb  
File Description: This file contains the best configuration for RNN based seq2seq model to generate data translations from english to tamil  
**data_preprocessing:**	Preprocess the dataset and pads the output and also responsible for Tokenizing.   
**seq_seq_model:**	    This function creats and returns the model.  
**inference_:**         This function performs the inference process to decode the given input.  
**decode_and_eval:**	  This function wil decode the inputs and also returns the val accuracy or Test accuracy based on the **test_f** flag value. If test_f is False this function will return val accuracy other wise it will return the test accuracy and creates the correct_preds.txt and wrong_preds.txt. 

File Name:Best_model_with_attention.ipynb  
File Description: This file contains the best configuration for RNN based seq2seq model to generate data translations from english to tamil  


File Name:Seq2Seq_with_attention.ipynb  
File Description: This file contains the wandb sweep configuration for RNN based seq2seq model with attention to generate data translations from english to tamil  









