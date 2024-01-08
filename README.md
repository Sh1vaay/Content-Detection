# Content-Detection Using LSTM and FNN

Spam Email Detection and Classification using LSTM and Feed Forward Neural Network:

The problem of spam emails has been a persistent issue in the realm of digital communication. Spam emails refer to unsolicited and unwanted messages that flood our email inboxes, often with the intent to promote products, services, or engage in fraudulent activities. These emails can be highly disruptive, time-consuming, and potentially harmful, as they may contain malicious links, malware, or phishing attempts. Addressing the problem of spam emails is crucial to ensure a smooth and secure email experience for users. Traditional rule-based filtering methods have limitations in adapting to evolving spam techniques, making it necessary to explore more sophisticated and adaptable approaches. Machine learning techniques, particularly those leveraging natural language processing and text classification, have shown promise in effectively identifying and filtering spam emails.

I began my project with three different datasets, each containing content relevant to my task. To create a comprehensive collection of labeled data for training and evaluation, I merged these datasets into a single dataset.

Next, I focused on preparing the data for model training by applying various natural language processing techniques. I started by converting all text data to lowercase to ensure consistency. Then, I removed punctuation marks from the text to focus on the essential content. Additionally, I eliminated commonly occurring words with little semantic meaning, known as stopwords, to reduce noise in the data. I further tokenized the text by splitting it into individual words or tokens, which would serve as the basic units for further analysis. To handle different word variations, I used stemming techniques to reduce words to their base or root form.

For predictive modeling, I implemented two different models: a Long Short-Term Memory (LSTM) model and a Feed Forward Neural Network (FNN) model. The LSTM model, a type of recurrent neural network (RNN), is particularly effective in capturing sequential information and long-term dependencies in text data. I trained the LSTM model on the preprocessed text data with the goal of predicting whether the content is relevant or unsolicited. The LSTM model demonstrated superior performance with an accuracy score of around 84%.

In contrast, the FNN model, a type of artificial neural network, did not perform as well as the LSTM model, achieving an accuracy score of around 62%. The FNN model operates by passing information in one direction, from the input layer through the hidden layers to the output layer.

To evaluate the models, I utilized various evaluation metrics such as accuracy, precision, recall, and F1 score. These metrics provided insights into the models' performance and their ability to correctly classify relevant and unsolicited content.

In conclusion, my project showcased the effectiveness of the LSTM model over the FNN model for the task of detecting relevant and unsolicited content. The LSTM model's accuracy score of 84% outperformed the FNN model's accuracy score of 62%. Additionally, I demonstrated the significance of incorporating natural language techniques, including lowercasing, punctuation removal, stopwords removal, tokenization, and stemming, in preprocessing textual data for model training.

