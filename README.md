# Chatbot
#### Python3x
Chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), patterns, and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
This chatbot is using NLTK, Keras, Python, etc.

The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

#### Prerequisites:
 - `pip install keras`
 - `pip install nltk`
 - `pip install tensorflow`
 - `sudo apt-get install python3-tk`



#### Files:
- intents.json: The data file which has predefined patterns and responses.
- train_chatbot.py: In this Python file, we wrote a script to build the model and train our chatbot.
- words.pkl: This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
- Classes.pkl: The class pickle file contains the list of categories.
- Chatbot_model.h5: This is the trained model that contains information about the model and has the weights of the neurons.
- Chatgui.py: This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

### Run the chatbot:

To run the chatbot, we have two main files; 
- train_chatbot.py
- chatapp.py.

First, we train the model using the command in the terminal:
- `python train_chatbot.py`
   - If we don’t see any error during training, we have successfully created the model. Then to run the app, we run the second file.

- `python chatgui.py`
    - The program will open up a GUI window within a few seconds. With the GUI you can easily chat with the bot.

##### You can customize the data(Intents.json) according to business requirements and train the chatbot with great accuracy.


