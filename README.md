A chatbot is a piece of software that can communicate and conduct tasks in the same way that a human can. Chatbots are widely utilized in customer service, social media marketing, and instant messaging with clients. Deep learning techniques are used to construct a very basic chatbot. The information will be used to train the chatbot, which will include categories (intents), patterns, and replies. A recurrent neural network (LSTM) is employed to classify which category the user's message belongs to, and then we choose a response from the list. The content of files is as follows: indents.json contains a dataset of predefined patterns and responses. The "train_chatbot" python file contains the script used for building and training the chatbot The "Chatbot_model" is the trained model Chatgui is the user interface that will be used by the users to interact with the chatbot

The 5 steps followed for creating the chatbot are:

- 1.Import and load the data file
- 2.Preprocess data
- 3.Create training and testing data
- 4.Build the model
- 5.Predict the response
<br />In order to run the chatbot GUI, first train the dataset by using the command: <br />
*python train_chatbot.py* <br />
If there are no compilation errors, the model has been created successfully, you can now run the GUI using:<br />
*python chatgui.py# Chatbot*
