# Hindi-to-English-NMT
A Neural Machine Translation model which takes as input a Hindi sentence and provides the corresponding English sentence as output. Sequence to Sequence architecture has been used to accomplish this task. 

#Seq2Seq

![image](https://user-images.githubusercontent.com/31798751/117764343-f0f6e080-b249-11eb-8d67-c19b9c92b5c9.png)

The Seq2Seq model architecture consists of a encoder and decoder , the encoder takes in the input Hindi sentence , learns its vector representation and then provides this learnt representation to the decoder , which predicts one word of the English sentence at a time, along with utilising the previous word generated as an output.


In the Hindi-to-English-NMT project, the Seq2Seq model architecture has been experimented with various different encoder and decoder models such as Recurrent neural network (RNN) , Long short-term memory (LSTM) , Gated Recurrent Unit (GRU) . Attention mechanism was also used in the further stages to further improve the results.
