# Zelle-Chatbot
### About
This repository contains the source code to create a Zelle chatbot, which can
answer basic FAQs (inspired from the ones found here: https://www.zellepay.com/faq/about-zelle)
as well as contact customer support. The steps for this task consisted of
creating an intents file (of intents, patterns, responses, and context),
data preparation (processing the intents file to be used for training),
building the deep learning model in Keras with TensorFlow as the backend,
and creating a GUI.

### Running the chatbot
To use this chatbot yourself, first download intents.json, train_chatbot.ipynb,
and gui_chatbot.ipynb (the other files do not make a difference as they will be
generated when the model is trained). Run train_chatbot.ipynb to build the model, then
run gui_chatbot.ipynb to start up the chatbot. If you do not see the chatbot window
pop up, check your taskbar to see if a new icon has popped up for the chatbot
window.

------------------------------------------------------------------------------

The language this program was coded in is:
	Python 3.9.2

------------------------------------------------------------------------------

The platform this program was developed on: <br />
&emsp;Edition:	Windows 10 Home <br />
&emsp;Version:	21H1 <br />
&emsp;Installed on:	3/15/2021 <br />
&emsp;OS build:	19043.1165 <br />
&emsp;Experience:	Windows Feature Experience Pack 120.2212.3530.0
