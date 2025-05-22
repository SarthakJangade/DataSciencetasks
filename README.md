## Auto Corrector Model
Description:
Spelling Correction
➡ Spelling Checker
➡Checks a word for spelling error.
➡Suggests a correction if needed.
Autocorrect
➡Check a word for spelling error.
➡Automatically picks the most likely word.

Applications of Spelling Correction :-
➡Search Engines.
➡Messaging Platforms.
 
Types of Spelling Errors
➡1.Non word errors
Any word not in the dictionary is an error.
Larger dictionary will lead to less non-word spelling errors.
How to correct non word spelling errors?
Let, Given an input word w, generate a of candidate C
w- thew
C={"the","then","there","they","..."}
Pick the word that maximizes the probablity using language model.
argmax P(c|w), for c Alt + 8712 Element of C
E.g.lanuage->> language 


➡ 2. Real word errors
1.words with similar pronounciations.
2.Words with similar spelling.
3.Choose the best candidate word.
4.Noisy channel model E.g probablistic model.
Steps :- 
1. Generate candidate words
2. Language Model
3. channel Model
4. Probability of the word
5.For each candidate word, product of the output of language model and channel model.

## Spam Classifier
Project Name:- SMS Spam Classification Model🤗 
Example :- 
Input Text:- URGENT! You have won a 1 week FREE membership in our $100,000 Prize Jackpot!
Output Label:- Spam
Input Text:- Do you have any queries!
Output Label:- Not Spam

Steps to build an model:-

1. Loading the Dataset
2. Pre-processing the Dataset
3. Feature Engineering
 i. Creating Meta Features
 ii. Counting Nouns and Verbs
 iii. Model Building for Meta Features
 iv. Tf-Idf Features
 v. Model Building for Complete Feature Set

## Next word recommendation system using language model.
Problem Statement: - To develop a next word recommendation system which should take in a seed text from the user as input and predict the next relevant word.

e.g.: - text = "how are"
Output: - "how are you"

About Dataset: - Taskmaster dataset, published in 2019.
 >64,777 conversational dialogue
 >Six domains:
 >ordering pizza,
 >creating auto repair appointments,
 >setting up ride service,
 >ordering coffee drinks,
 >making restaurant reservations.
Dataset link: - https://lnkd.in/g6p_meVD
Steps to build the next word recommenders' system.

1.Loading and exploring the dataset

2.Creating N-grams of the dialogue

3.Building the N-gram Language Model

4.Predicting the next word using N-gram Language Model
