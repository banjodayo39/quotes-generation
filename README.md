# quotes-generation
This demonstrate generation of quote text using charactered based RNN, the data set used is a list JSON file of a list of quotes, and their authors.  Given a sequence of characters from this data, we will  train a model to predict the next character in the sequence.

<a href="https://colab.research.google.com/drive/1jOc295NydznTdRCsA9nmQJA3Nr_nbqXx#scrollTo=oDmG9Lv3ZqGP">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


##  Focus Area: Language Modeling 
Language Modeling is the ability to predict the next word or character since characters made-up a word. “man” is a word that has 3 characters: ‘m’, ‘a‘, ’n’. It cut across various applications such as speech recognition, optical character recognition, text generation, handwriting recognition, machine translation, and spelling correction.
Commonly, found application is in our phone keyboard, which suggests a text to us while typing.
“ …I am going to the …..”,
The sentence could be completed by using the following words: market, hospital, farm.
“I am going to the market”, “I am going to the hospital”, “I am going to the farm”.
The task of predicting the next word is what language modeling is all about in natural language processing (NLP), using machine learning to predict (guess) the word. How can we achieve this in NLP?
