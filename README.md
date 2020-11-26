#  DUPLICATE QUESTION PAIR DETECTION

## Abstract
A forum which is growing like Quora comprises a set of queries(questions) and answers created by a user. The users create, edit, and arrange the questions and responses. A huge number of Users on the Quora platform makes it inevitable to have multiple queries of similar intention from different users, this raises the problem of having questions that are redundant. It will be easier to find high-quality answers and save time by identifying duplicate questions efficiently. In this paper, we have exploited the techniques of BoW, TF-IDF and Universal Sentence Encoder for identifying pair of duplicate questions from the publicly available dataset which was released by Quora, and have been able to achieve better results in terms of accuracy than the onces used previously for the same purpose.

## Base Paper
Base paper is from stanford college and can be found on the below link
https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1174/reports/2761178.pdf

##  Dataset
Quora, an official QA platform , released a public tsv file which consists of question pairs and information about whether the question are duplicate or not.The dataset consist around 404k pairs of questions and their labels. Dataset can found on the below link:
http://qim.fs.quoracdn.net/quora_duplicate_questions.tsv

## Run Code On Colab
Please visit following google colaboratory link to run the code

- BoW and TF-IDF model:
https://colab.research.google.com/drive/1VffAsocswnI5DNU6M1wyPGqm_nLWq-vK

- Universal Sentence Encoder along with Keras Model
https://colab.research.google.com/drive/1kB7Zr0Rzxc4nY4TAr2C2rnQcZUrQzMEI

## Results

Please open .ipynb files to view the result
- QuoraDuplicationDetection.ipynb file contain code and result of BoW and TF-IDF model.
- QuoraDuplicationUSE.ipynb file contain code and result of Universal Sentence Encoder with Keras model implementation

## Team Members

- Aditya Karia (171IT203)
- Shashank Jaiswal (171IT239)
- Thejaswini D M (171IT243)
