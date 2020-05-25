# Recommend similar apparel products in e-commerce using product descriptions and Images
Suggest the similar product to an user based on the project he/she is intrested in.
<h2> Link to dataset </h2>
https://drive.google.com/open?id=1Fif_JbnDnujlEPuPan1mt8HHuvjFevOJ
<h2>Business Objectives</h2>
<ol>
  <li>No Low-latency requirement</li>
  <li> Errors can affect the sell</li>  
</ol>
<h2>Data Overview</h2>
<ol>
  <li>Number of data points :  183138</li>
  <li>Number of features/variables: 19</li>
</ol>
I am processing only 28K points so that I can run this code on my laptops in a reasonable amount of time.
<h2> Summary </h2>
In this project I have used<ol>
  <li>BOW</li>
  <li>tf-idf vectorizer </li>
  <li>Word2Vec</li>
  <li>avg Word2Vec</li>
  <li>tfidf weighted Word2Vec </li>
  </ol>in order to vectorize the title of product and then applied cosine simlarity to find the similar products.
  
  
