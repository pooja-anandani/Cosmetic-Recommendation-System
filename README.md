# Cosmetic-Recommendation-System

Choosing the new cosmetic product can be tiresome for many reasons we are not aware of many of the products that are used and also how it will suit our 
skin type. This content-based recommendation model is processed via word embedding I have used the machine learning algorithm t-SNE and visualization library 
known as bokeh. 

1) After understanding the data we can focus on particular ingredient based on the skin types provided. 

2) Tokenization of ingredients is done to make a binary bag of words. Bag of words is an important concept in Natural Language processing
   the document having similar word can be similar to each other. 

3) Document term matrix is created where M= cosmetics N= Ingridents.If a ingrident is there in a cosmetic the value would change to 1 or it will be 0. 

4) Dimensionality Reducation using t-sne that is an abbrivated term for T-distributed stochastic neighbor embedding it is a non-linear dimensionality
   reduction technique by keeping similarity between instances. 
   
   Future Scope: 
      Integration with web-application and use in real-time in the website that sells skin products
