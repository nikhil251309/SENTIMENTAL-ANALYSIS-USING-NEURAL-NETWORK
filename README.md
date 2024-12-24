# SENTIMENTAL-ANALYSIS-USING-NEURAL-NETWORK
 OBJECTIVE: The project aims to perform sentiment analysis on movie reviews, classifying them as positive or negative using neural
 network techniques.
 
 TECHNIQUE AND TOOLS: 1) DATA PRE-PROCESSING: Removal of tags, punctuations, and stop words; text normalization using libraries
 like TensorFlow.
 2) MODELS: Simple Neural Network (SNN) Embedding, flattening, and dense layers. Convolutional Neural Network (CNN) is used
 primarily for image recognition. Recurrent Neural Network (LSTM) for sequential data.
 
 SOLUTION PROCESS: 1) Using a dataset of 50,000 IMDb reviews.
 2) Tokenized reviews, padded sequences to a uniform length.
 3) Implemented three architectures SNN, CNN, and LSTM.
 4) Trained models on 80% of the data and validated the remaining 20%.

 ACCURACY: SNN: 85.7%, CNN: 86.2%, LSTM: 86.2%
 
 LSTM and CNN showed slightly better performance due to handling sequential dependencies and capturing local features, respectively.
