# Movie Recommendation System
      - Dataset has 5000 movie names and it details in 23 columns (23 features)
      - simce the dataset is in 2 csv files, we merge them wrt movie id.
      - since not all columns are needed, we select only those that we need.
      - checked for null values 
      - checked for duplicate enties 
      - data is preprocessed ( helper functions to pick out just what is needed)
      - all the words which describe the movie , keywords , director's name , prominent actor's name , all these words are grouped together 
      - stemming is done to remove all the prefix and sufix from the tags created
      - all the words are kept in lower case 
      - stop words removal while vectorisation 
      - porter stemmer from nltk library 
      - count vectoriser from sklearn
      - using cosine similarity similarity between all the tags of the movies created is calculated 
      - similar movies are recomended by a function using the similarity matrix created which is 4806*4806
      - using pickle , similarity matrix and list of movies is dumped in a file 
      - using streamlit , movie recomendation app is deployed 
        
