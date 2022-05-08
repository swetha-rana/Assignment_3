# Assignment_3

This Repository contains the 7 files they are: Best_model_with_attention.ipynb, Best_model_without_attention.ipynb, Seq2Seq_with_attention.ipynb, rnn_seq_to_seq.ipynb,Test_Data_Predictions_with_attention.csv,Test_data_prediction_without_attention.csv

**File Name:** **rnn_seq_to_seq.ipynb **  
**File Description:** This file contains the wandb sweep configuration for RNN based seq2seq model to generate data translations from english to tamil  
By changing sweep config we can select the parameters values to experiment. 

**Important Functions:**  
**data_preprocessing:**	Preprocess the dataset and pads the output and also responsible for Tokenizing.   
**seq_seq_model:**	    This function creats and returns the model.  
**inference_:**         This function performs the inference process to decode the given input.  
**decode_and_eval:**	  This function wil decode the inputs and also returns the val accuracy or Test accuracy based on the **test_f** flag value. If test_f is False this function will return val accuracy other wise it will return the test accuracy and creates the correct_preds.txt and wrong_preds.txt.  

**File Name:** **Best_model_without_attention.ipynb**  
**File Description:** This file contains the best configuration for RNN based seq2seq model to generate data translations from english to tamil  
  
**Important Functions:**  
**data_preprocessing:**	Preprocess the dataset and pads the output and also responsible for Tokenizing and returns the input output texts and tokens,etc.,     
**seq_seq_model:**	    This function creats and returns the model.  
**inference_:**          This function builds the inference model   
**decode_and_eval:**	  This function wil decode the inputs and also returns the val accuracy or Test accuracy based on the **test_f** flag value. If test_f is False this function will return val accuracy other wise it will return the test accuracy and creates the correct_preds.txt and wrong_preds.txt. 



**File Name:** Seq2Seq_with_attention.ipynb  
**File Description:** This file contains the wandb sweep configuration for RNN based seq2seq model with attention to generate data translations from english to tamil  
**Important Functions:**  
**data_preprocess** : This function preprocess the data and returns the input characters, Target characters and their lengths etc..,  
**one_hot_coding** : This function takes the data as input and returns onehot encoding of data.  
**build_model** : This function creats the LSTM,GRU,RNN models based on the rnn_type variable value and return the model.  
**build_inference_model** : This function builds the inference model.    
**train** : This function compiles and trains the model.  


**File Name:** Best_model_with_attention.ipynb  
**File Description:** This file contains the best configuration for RNN based seq2seq model to generate data translations from english to tamil  
**Important Functions:**  
**data_preprocess** : This function preprocess the data and returns the input characters, Target characters and their lengths etc..,  
**one_hot_coding** : This function takes the data as input and returns onehot encoding of data.  
**build_model** : This function creats the LSTM,GRU,RNN models based on the rnn_type variable value and return the model.  
**build_inference_model** : This function builds the inference model.    
**train** : THis function cimpiles and trains the model.  
**calculate_accuracy** : this function perfroms the calculation of accuracy.  
**decode_best_model** : This function perfroms the decoding of the data and returns the decoded word and attention.


**File Name:** Test_Data_Predictions_with_attention.csv  
**File Description:** This file contains the Test data predictions of seq to seq model without attention  


**File Name:** Test_data_prediction_without_attention.csv  
**File Description:** This file contains the Test data predictions of seq to seq model without attention  

**File Name:** Readme.md  
**File Description:** This file contains the important information of this repository  






