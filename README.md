# Sentimental_analysis
# What is Sentimental Analysis?
 Well we can define sentiment analysis is a process of computationally identifying and categorizing opinios from a piece of text, and determine the writer's attribute towards a particular topic or the product, is weather postive, negative, or neutral.
  Consider a situation..
 Let say you have an company, now the success of the company or a product directly depends on its customer. Now if the customer like your product its  a success if they dont like your product you need to improvise by making some changes in it. 
 So the next question comes to mind is how will you know if a customer likes your product or not for that you need to analyse the customer.  And one of the attribute of analysing your customers is to analyse the sentiment of your customers. 
And this is where Sentimental Analysis comes into picture.
# How does it actually words?
Lets take this sentence as an example:
*The movie was great!*
Now the very first step is Tokenization.
## Tokenization
What exactly is tokenization, its nothing but dividing your para/sentence into different set of statements.
 - The 
 - movie
 - was
 - great
 - !   
##  Cleaning the data
Now in this step what we do is we remove all the special characters which do not value the analytics part. 
- The 
- Movie
- Was 
- Great
- ! *-we do not need this* 
## Removing the stop words
Now we also remove the stop words like the was these words dont really add anything to the analytics parts.
Movie
Great
## Classification 
Now in these steps your task is to classify the words whether it is a positive word, negative or a neutral word. For positive we give a score of +1 for negative -1 and neutral we give 0.
### Apply supervised Algorithms for Classification:
This is the part where machine learning comes into the picture. We can model our data with a bag of words or we can use Lexicons, which are nothing but a Dictionary of words with a pre-classified set of words.
Once the model is trained we can use it for testing the analysis of the statements. More the accuracy of score better is your algorithm or the classification.
 Movie- neutral:=0
Great- positive:-1
 Overall score 1+0=1
So its a positive statement.
