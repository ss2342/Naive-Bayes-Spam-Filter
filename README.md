# Naive-Bayes-Spam-Filter

<b>The .ipynb files are too large and may not load on github so use these three links to view the notebooks:</b>

https://nbviewer.jupyter.org/github/ssingh1997/Naive-Bayes-Spam-Filter/blob/main/Bayes_Classifier_Preprocessing.ipynb
https://nbviewer.jupyter.org/github/ssingh1997/Naive-Bayes-Spam-Filter/blob/main/Bayes_Classifier_Training.ipynb
https://nbviewer.jupyter.org/github/ssingh1997/Naive-Bayes-Spam-Filter/blob/main/Bayes_Classifier_Testing.ipynb

In this project, I built a simple naive bayes spam filter. Using the "bag of words" approach, I created a naive bayes model from scratch from an immense dataset of spam and non-spam emails. I then compared my results with the scikit-learn's implementation of naive bayes.

For Naive Bayes Model From Scratch, there were 3 Stages: Preprocessing, Training, and Testing

<b>Preprocessing Stage:</b>

  Opean, Read, and Extract Raw Data File with all the emails and their labels (spam vs non-spam) using Generators
  
  Clean Data
  
    Check for missing values
    Add Document IDs to Track Emails in Dataset
  
  Save cleaned data to File
  
  Visualize Spam Messages using Pie charts 
  
  Use NLP for the following tasks
  
    Convert everything to lower case for consistency
    Tokenising, meaning that we will split up individual words in a sentence
    Remove stop words (i.e: "the, of, am, on, I")
    Strip out HTML tags
    Word stemming (i.e. "going", "gone", "goes" will all be treated as "go")
    Remove Punctuation
    
  Create Word Clouds to see which words occur most often in spam and non-spam emails
  
  Create a Vocabulary DataFrame 
  
  Generate Features DataFrame and create a Sparse Matrix for Training and Test Data
  
<b>Training Stage:</b>

  Read and Load Features into Numpy Arrays
  
  Train Naive Bayes Model 
  
    Calculate Probability of Spam
    Calculate Total Words 
    Sum Tokens occuring in Spam and Non-Spam 
    Find P(Token|Spam), P(Token|Non-Spam), and P(Token)
    
  Save Trained Model 
  
  Prepare Test Data
  
<b>Testing Stage:</b>

  Load Data
  
  Calculate the Joint Probability 
  
  Make Predictions
  
  Use accuracy, precision, recall, and F-score to measure how well our model works
  
  Visualized Naive Bayes Classifier using scatter plot and created decision boundary


    
  
  
  
    
