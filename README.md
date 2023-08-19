# chatbot

A chat bot using PyTorch

## How to run the code

1. Run `python ./train.py`. This will train the model using the data in the `intents.json`, and it will save the model states to `data.pth`.
2. Run `python ./chat.py`. This will start the chat bot on the terminal. You can exit the program by typing `quit`.

## Dependencies

- [PyTorch 2.0.1 with Cuda 11.8](https://pytorch.org/)
- [NLTk 3.8.1](https://www.nltk.org/index.html)
  - This is used for tokenization and stemming the text

