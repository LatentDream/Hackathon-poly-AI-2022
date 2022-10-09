# Hackathon-poly-AI-2022

## Language identification (Challenge 1)
Description of the challenge
Difficulty : MEDIUM

Language detection is a very important step in many other NLP based machine learning models like text classification tools or task facilitation tools like translating or speech to text software.

This problem is an Natural Language Processing problem. The main challenge is to first convert the text (String) into vectors that are readable by your machine. We advice you to make some research on what is a “token”, and what is “word embedding”. Here is some useful keywords to for your research (Tfidf, word2vec, ngram …). For this challenge you can use any library you desire (sklearn, tensorflow, pytorch…)

The provided dataset contains 31012 labeled text in 28 languages. Some sentences can be amazon reviews, others are random sentences.
In total, there are 24326 training samples and 6686 testing samples. For each sample, you have a label which corresponds to one of the 28 languages :
['Turkish', 'Korean', 'Arabic', 'English', 'Swedish', 'Tamil', 'Greek', 'Dutch', 'Portugese', 'Latin', 'French', 'Persian', 'Chinese', 'Spanish', 'Estonian', 'Indonesian', 'Romanian', 'Thai', 'Malayalam', 'Hindi', 'Russian', 'Japanese', 'Italian', 'Pushto','Kannada', 'Urdu', 'German', 'Danish']

Nb data in train: 8216
Nb data in test: 8052

### Code
Basic statistical problem

### Result 
~75% accuracy
-> A lot of text was multilanguage because of tweet and amazon review


## Does this plant have a disease? (Challenge 6 (HARD))
Description of the challenge
Difficulty : HARD

Plant pathology is the scientific study of diseases in plants caused by pathogens and environmental conditions. Plant diseases are a normal part of nature and one of many ecological factors that help keep the hundreds of thousands of living plants and animals in balance with one another. However, when tardily detected, and subsequently left untreated, they can be the cause of loss of crops for example. Plant disease may also result in hunger and starvation, especially in less-developed countries where access to disease-control methods is limited and annual losses of 30 to 50 percent are not uncommon for major crops.

In this problem, you have to find a way to load and classify images.
Here are a few resources that might help:
- The basic library in python to load images: https://pillow.readthedocs.io/en/stable/reference/Image.html
- IBM’s introduction to convolutional neural network https://www.ibm.com/cloud/learn/convolutional-neural-networks
For this challenge you can use any library you want.

The provided dataset contains images in 13 differents classes, which are:
['Pepper bell Bacterial spot', 'Pepper bell healthy', 'Potato Early blight', 'Potato Late_blight', 'Potato healthy', 'Tomato Bacterial spot', 'Tomato Early blight', 'Tomato Late blight', 'Tomato Leaf Mold', 'Tomato Septoria leaf spot', 'Tomato Spider mites Two spotted spider mite', 'Tomato TargetSpot', 'Tomato Tomato YellowLeaf Curl Virus', 'Tomato Tomato mosaic virus', 'Tomato healthy']

Given an image, your job is to predict which type of plant it is and if it is healthy or which type of disease it has.


### Code
CNN model for image classification

### Results

Second place !:)

  |     | Accuracy         | F1_score     | Robustness        | Score  |
  |-----|------------------|--------------|-------------------|--------|
  |#1   |95.41 %	         |95.11 %       |	86.1 %          	|90.38 % |
  |#2 US| 97.04 %          | 97.2 %       | 83.82 %	          | 90.02 %|
  |#3   |94.54 %	         |94.05 %	      |80.84 %	          | 86.95 %|
  | ... | ...              | ...          | ...               | ...     |






