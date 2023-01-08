# Stress_Detection

Stress, anxiety, and depression are threatening the mental health of people. Every person has a reason for having a stressful life. People often share their feelings on social media platforms like on Instagram in the form of posts and stories, and on Reddit in the form of asking for suggestions about their life on subreddits.     
The dataset I am using for this task contains data posted on subreddits related to mental health. This dataset contains various mental health problems shared by people about their life. Fortunately, this dataset is labelled as 0 and 1, where 0 indicates no stress and 1 indicates stress.       
##  Libraries used  
Pandas    
Numpy   
Sklearn   
Nltk    
Re

##    Process   
First, we manipulate the dataset to remove all Non-Alphabet characters from the data.  
Then we perform Stemming on the words that are left in the messages, after which we Vecorize them using the Count Vectorizer.    
Lastly, we fit this data into a model that uses the Bernoulli NB algorithm.   

This is how the working model looks:   
<img width="321" alt="Screenshot 2023-01-08 at 2 38 23 PM" src="https://user-images.githubusercontent.com/72307339/211188432-061353ba-681d-465e-9ebf-45327e227933.png">     

<img width="537" alt="Screenshot 2023-01-08 at 2 39 15 PM" src="https://user-images.githubusercontent.com/72307339/211188458-9a8dfe10-0ef6-40f2-9b67-f7849db1e8d7.png">
