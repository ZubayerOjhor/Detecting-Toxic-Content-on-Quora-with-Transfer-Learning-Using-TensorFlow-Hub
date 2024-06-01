# Detecting-Toxic-Content-on-Quora-with-Transfer-Learning-Using-TensorFlow-Hub
This project demonstrates the use of transfer learning for text classification, specifically focusing on identifying insincere questions on Quora. By leveraging pre-trained models from TensorFlow Hub, such as Universal Sentence Encoder, NNLM, and BERT, the project aims to improve model generalization and save training resources.

About the Dataset:
I used the Quora Insincere Questions Classification dataset, which includes unique question identifiers, question texts, and labels indicating whether a question is insincere.

Learning Objectives:

Utilize various pre-trained NLP text embedding models from TensorFlow Hub.
Perform transfer learning to fine-tune models on custom text data.
Visualize model performance metrics with TensorBoard.
Project Tasks:

Setup TensorFlow and Colab Runtime:

Downloaded and imported the Quora Insincere Questions dataset.
Processed the text data into question vectors and labels.
TensorFlow Hub for NLP:

Employed text embedding models like Universal Sentence Encoder, NNLM, BERT, and Wikiwords.
Define Function to Build and Compile Models:

Built the model using TensorFlow's Sequential API, incorporating dense layers with activation functions.
Train Various Text Classification Models:

Trained models using gnews-swivel-20 dim, nnlm-en-dim50, nnlm-en-dim128, and universal-sentence-encoder.
Compare Accuracy and Loss Curves:

Analyzed and compared the performance of each model.
Fine-tune Models from TF Hub:

Fine-tuned the models to enhance their accuracy.
Visualize Metrics with TensorBoard:

Visualized accuracy and loss curves to evaluate model performance.
Comments on the Results:
Fine-tuned models exhibited improved accuracy, with smaller dimension models like gnews-swivel-20 dim achieving results comparable to larger models such as nnlm-en-dim128 and universal-sentence-encoder (512 dim). The fine-tuned Universal Sentence Encoder model (512 dim) outperformed others, indicating that higher dimension models tend to perform better.

Conclusion:
This project demonstrated the effectiveness of transfer learning in NLP text classification, showcasing the potential for applying these techniques to improve online interactions. 
