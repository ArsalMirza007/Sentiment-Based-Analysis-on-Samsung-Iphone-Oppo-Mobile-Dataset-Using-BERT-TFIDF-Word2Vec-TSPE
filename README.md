# Sentiment-Based-Analysis-on-Samsung-Iphone-Oppo-Mobile-Dataset-Using-TF-IDF-Word2Vec-TSPE
# Instructions:
The provided code performs the following tasks for text classification using various algorithms:

1. **Library Installation and Imports**:
   - The code starts by installing necessary libraries like TensorFlow and Transformers using pip. Then, it imports required modules and libraries.

2. **Defining Tweet Class and Methods for Data Loading and Cleaning**:
   - A class called `Tweet` is defined to represent tweets with attributes like UID, content, and sentiment.
   - Methods for cleaning tweet content, loading stop words, and reading files containing tweets are defined.

3. **Defining Method for Showing Results**:
   - A method is defined to plot confusion matrix and display F1 score.

4. **Data Loading and Preprocessing**:
   - Tweet data is loaded, preprocessed, split into training and testing sets, tokenized, and sequences are padded to have the same length.

5. **Hyperparameter Optimization (Optional)**:
   - An optional step where hyperparameters are optimized using the hyperopt library and the TPE algorithm. This step aims to find the best hyperparameters for the model.

6. **Model Training**:
   - A model, typically an LSTM model, is trained with the best hyperparameters obtained from hyperparameter optimization or with predefined hyperparameters.

7. **Visualizing Training History**:
   - Training and validation accuracy, as well as loss, are plotted over epochs to visualize the model's performance during training.

8. **Model Evaluation**:
   - The trained model is evaluated on the test set to calculate the F1 score and display evaluation results including the confusion matrix.

9. **Output**:
   - The code provides output such as the best hyperparameters and their performance obtained from hyperparameter optimization (if performed), as well as the model's performance metrics like accuracy, loss, and F1 score.

# All details including the screenshots are pasted in the docx file.
[Algo_Details.docx](https://github.com/ArsalMirza007/Sentiment-Based-Analysis-on-Samsung-Iphone-Oppo-Mobile-Dataset-Using-TF-IDF-Word2Vec-TSPE-/files/14472199/Algo_Details.docx)
