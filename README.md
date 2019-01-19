/*

    Author :: Raj Mehrotra
    Date:: 20-01-2019
    
 */

# Spooky-Author-Identification : Kaggle Competition

The notebook on famous Kaggle competition : Spooky Author Identification.  

The dataset has around 20K texts each of which is written by one of the 3 authors.**The task is to identify the authors from their respective texts or work.**

I have first cleaned and pre-processed the text using  **standard NLP techniques like tokenization , stemming or lemmatization , stop-word removal etc....** I have also tried to create some **meta features or hand-crafted features based on the author writing pattern.**

I have used the **traditional BOW approach with TFIDF Vectorizer and the Count Vectorizer and then deployed ML algos like LogisticRegression and Naive Bayes which are well suited for text data.**

I have also tried to use the **pre-trained Google word2vec word embeddings** which have been trained on a corpus of 3 Billion words from Google News. **For the words not present in the corpus one can use a fix <UNK) token to represent those words.**

For me tfidf on count vectorizer gave best results till now. **My submission scored a multi-class log loss of 0.46 on kaggle private LB which is quite decent.**
