# Spam-detection
Implementation of  Artificial Neural Network (ANN) for email spam-detection using TensorFlow  

The program is able to detect spam with up to 99.6% accuracy.

*The code is tested on python 2.7.11 and should work on python 2.x*

-------------------------------------------------------------------------------------------------------------------------
## Files description:

Data for this project is from a Kaggle competition(https://inclass.kaggle.com/c/adcg-ss14-challenge-02-spam-mails-detection) 

- `TR.tar.gz` FILES contains 2500 mails both in Ham(1721) labelled as 1 and Spam(779) labelled as 0
- `spam-mail.tr.label` is the associated training labels.
- `ExtractContent.py`  extracts the subject and body of the email.

> In a python compatible environment, 

> 1, invoke the script by command 

> ./ExtractContent.py

>  2, input source directory -- choose where to store the source files

>  For exmaple
   C:\EMAILPro\CSDMC2010_SPAM\TEST

> 3, Choose where to store the results

> For example
  C:\EMAILPro\CSDMC2010_SPAM\TEST_NEW
    
> 4, Compelete.

- `email_input.py`  vectorize the emails text,and outputs  trainX.csv, trainY.csv, testX.csv, and testY.csv 
- `data.tar.gz` contains trainX.csv, trainY.csv, testX.csv, and testY.csv
- `BagOfWords.p` contains all unique words from the data to use it later 
- `Spam detection.ipynb` Ipython notebook that trains the model and calls emails from a Gmail account to for classification

#### The email format description:
 
*The format of the .eml file is defined in RFC822, and information on recent 
standard of email, i.e., MIME (Multipurpose Internet Mail Extensions) can be
found in RFC2045-2049.*

#### NOTE:
*The notebook contains info describing how the model works , and how to authenticate your Gmail to test it out!*


