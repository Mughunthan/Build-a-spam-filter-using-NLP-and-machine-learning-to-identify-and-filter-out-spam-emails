## Developed a robust Spam Email Filter using Natural Language Processing (NLP) techniques and machine learning algorithms. The goal is to create an intelligent system capable of accurately classifying emails as either spam or legitimate (ham) based on their content and linguistic features.

### Flowchart of the code:

1. **Data Loading and Inspection:** The code loads the Spam Email Dataset and inspects its columns.

2. **Text Preprocessing:** It preprocesses the email text by tokenizing, removing stop words, and converting to TF-IDF vectors. This step prepares the data for machine learning.

3. **Machine Learning Model:** It uses a Support Vector Machine (SVM) classifier to train a model on the preprocessed text data.

4. **Model Evaluation:** The code evaluates the trained model's performance using accuracy score and classification report, which show how well the model can classify emails as spam or legitimate based on their content.

