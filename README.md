# RecommendationSystem
This work presents a study on building a recommender system using the Amazon product review dataset. The goal of the system is to provide personalized recommendations to customers, based on their purchasing habits and preferences. 

### Dataset
The dataset was collected by a researcher at UCSD and contains Amazon reviews in the range May 1996 - Oct 2018~\cite{ni2019justifying}. It includes reviews~(rating, review text, review time, and etc.), product metadata~(description, category, price, brand, and etc.). The total number of reviews is 233.1 million.

The whole dataset is very huge and not practical for us to deal with. Therefore, in this project, we choose one specific category, \texttt{Electronics}.

The electronics reviews data include 20,994,353 records of reviews and ratings. The electronics metadata include 786,445 records of products and 19 columns. Some important columns in metadata include:
\begin{itemize}
    \item asin - the unique ID associated with each product
    \item description - The product’s description
    \item categories - a python list of all the categories each product falls into
    \item price - the price of the product
    \item rank - the ranking of each product within a specific category
    \item brand - the brand of the product
    \item main\_cat - the main category of the product.
\end{itemize}


### Methods
The study investigated several approaches such as collaborative filtering to generate recommendations, where users are recommended products that are similar to those that they have previously rated highly. 
The performance of the system was evaluated using root mean squared error~(RMSE). The results show that the system is able to provide accurate and relevant recommendations to customers. 
