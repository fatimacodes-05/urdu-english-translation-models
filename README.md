# urdu-english-translation-models
A comparative implementation of sequence-to-sequence models using RNN,BIDIRECTIONAL RNN,LSTM and Transformer architectures for Urdu-to-English neural machine translation. Includes preprocessing, training, and evaluation steps.

##  Data Preprocessing
- Loaded dataset using `pandas`
- Tokenized English and Urdu sentences
- Padded sequences to a fixed length for both input and output
- Maintained consistent vocabulary size and padding across all models
  
##  Models Implemented
Trained the following sequence-to-sequence models for English-to-Urdu translation:
1. **RNN-Based Seq2Seq**
2. **Bi-directional RNN**
3. **LSTM-Based Seq2Seq**
4. **Bi-directional LSTM**
5. **Transformer Model (Multi-head Attention)**
   
 ## 🛠 Training Configuration
- All models trained for **50 epochs**
- Same training, validation, and test splits used across all models
- Hyperparameters such as learning rate, batch size, dropout rate, optimizer, and number of layers were tuned individually
  
  ##  Evaluation
- Used a fixed set of test English sentences for comparison
- Evaluated all translations using **BLEU Score**
  
Asma Fatima - Full implementation, documentation, and report
