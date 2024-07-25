
<h1><b> Hate Speech Detection on Twitter platform</b></h1><br>
<h1>Group - 2 </h1><br>
<h3>Problem Statement</h3>
In today's digital age, hate speech on online platforms is a growing concern that impacts individuals and communities globally. Social media platform like Twitter host billions of users who generate a vast amount of content daily. The business problem we are addressing is the need for an efficient, scalable, and accurate system to automatically detect and mitigate hate speech in user-generated content on Twitter platform
<br>
<h3>Solution Description</h3> 
To address the problem of hate speech on Twitter platform, we propose developing a machine learning model that can automatically detect and categorize user-generated content into hate speech/offensive language and neutral content. The solution involves the following steps: 

#Data Collection: Gather a diverse and comprehensive dataset of user-generated content from Twitter platforms.<br>

#Data Labeling: Ensure accurate labeling of content into the categories of hate speech/offensive language, or neutral.<br>

#Model Training: Use the labeled dataset to train a robust machine learning model.<br>

#Evaluation: Test and validate the model to ensure high accuracy and reliability in detecting hate speech.

#Deployment: Integrate the model into online platforms to assist in real-time content moderation.<br>


<h3>Dataset</h3>
Selected Davidson dataset has over 24,000 entries, covering a wide range of hate speech scenarios and user-generated content from Tweeter platform. Each tweet is labeled as hate speech, offensive language, or neutral content.

<h4>Dataset Size:</h4>

  #Hate speech -20609

  #Non Hate speech- 4159
  
<h4>Origianl Dataset link : </h4>
https://drive.google.com/drive/folders/1sCNO7onQ-kzQJUYitV-PtZzQtGrnD7jh?usp=sharing<br>


<h3>Data Preprocessing</h3>

Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model. It is the first and crucial step while creating a machine learning model. 
 
  #Recategorization: Labeled Hate speech and offensive language as 0, non-hate speech as 1

  #Handling missing values: Replaced with empty strings

  #Handling duplicates: Removed duplicates
  
  #Handling abbreviations: Replaced with full forms
  
  #HTML entity decoding: Decoded HTML entities
  
  #Contraction expansion: Expanded contractions
  
  #Normalization: Applied normalization to the data

<h4>Preprocessed Dataset link : </h4>
https://drive.google.com/drive/folders/1sCNO7onQ-kzQJUYitV-PtZzQtGrnD7jh?usp=sharing<br>


<h3>Tokenization and Embedding</h3>

Tokenization : Word Tokenization

  Word tokenization divides the text into individual words. In this tokenization technique, words are treated as the basic units of meaning.
  
Embedding technique : TF – IDF Encoding 

TF-IDF is a numerical statistic that reflects the importance of a word in a document. The TF-IDF algorithm takes into account two main factors: the frequency of a word in a document (TF) and the frequency of the word across all documents in the corpus (IDF).<br>



<h3>Modeling</h3>

Implemented various Machine Learning models and Deep Learning models including:

<h4>Machine Learning Model:</h4>

1. Random Forest Model
2.  Naive Bayes Model
3.  Logistic Regression Model

<h4>Deep Learning Models:</h4>

1.   Artificial Neural Network (ANN)
2.   Convolutional Neural Networks (CNN)<br>


<h4>Finalized Deep Learning Model : Convolutional Neural Networks (CNN)</h4>

The architecture of CNNs is inspired by the visual processing in the human brain, and they are well-suited for capturing hierarchical patterns and spatial dependencies.
#Reasons for choosing Convolutional Neural Networks Model:
 
1. CNNs are relatively robust to noise and variations in the input data.
2. CNNs can be adapted to a variety of different tasks by simply changing the architecture of the network.
3. CNNs can be very efficient, especially when implemented on specialized hardware such as GPUs.	Confusion Matrix of CNN Model 




<h3>Evaluation Matrix</h3>

<h4>Key Matrix for Evaluation: F1 Score</h4>

The F1 score is the harmonic mean of precision and recall, providing a single metric to assess the balance between the two.<br>

F1 Scores Achieved Using Convolutional Neural Networks (CNN):


Class 0 (Hate Speech): 0.96

Class 1(Non Hate Speech): 0.80











<h4>The individual implementations of the models can be found in separate branches of the repository. Each team member experimented with different approaches and models, and we decided to use the best methods from these individual efforts.</h4>
