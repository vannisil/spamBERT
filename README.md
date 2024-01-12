
# spamBERT - BERT pre-trained model for spam classification

spamBERT is a project that utilizes BERT, a pre-trained language model, for the purpose of spam classification. Leveraging BERT's contextual understanding of language, the model is fine-tuned on a dataset of spam and non-spam messages. 

## Directory tree

- **data**: contains the datasets used for the project;
- **model**: contains the BERT classifier class and the methods to train, evaluate and test the model;
- **static**: contains che CSS file and the logo file used to develeop the frontend, using _Flask_ framework, made up in order to use the model with a graphic interface;
- **templates**: contains the HMTL file used by Flask;
- **utility**: contains the custom dataset written in order to read correctly datas for our datasets and some utility methods, like the loading data function.
Outside every directory there are three files:
- **app.py**: this code runs the Flask app;
- **exec_app.py**: allow the user to run the app like an internal program on the machine;
- **inference.py**: allow the user to test the model inside the IDE.

## The dataset

Our datasets, SMS Spam Collection and Spam-Ham Dataset are two collection of spam and not-spam SMSs and e-mails. Every sample has two features: the target features, "ham" or "spam" in order to define if a text is considered not-spam or spam, and the main features that contains the text.

![dataset](https://i.ibb.co/xFWLtR0/Screenshot-2024-01-12-alle-09-25-10.png)

## spamBERT architecture

Our architecture includes the pre-trained BERT base (with 12 encoders) and a fully connected layer. We used this model and we have fine-tuned it in order to perform well on our task. We obtained an accuracy score of _99%_.

## Results
The interface of our project is the following:
![interface](https://i.ibb.co/jgwQ76D/Registrazioneschermo2024-01-12alle09-38-01-ezgif-com-video-to-gif-converter.gif)

## Authors

- [Davide Abbattista](https://www.github.com/davide-abbattista)
- [Giovanni Silvestri](https://www.github.com/vannisil)
