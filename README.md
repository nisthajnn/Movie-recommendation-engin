# Movie-recommendation-engine

Content based movie recommender system recommends similar to the movie user likes.
The details of the movies(title,genres,runtime,rating,poster etc)are fetched using an api based TMDB.

How to run the Project?

Clone my repository
open CMD in working directory
run following command
pip install -r requirements.txt
Get your API key from https://www.themoviedb.org/. 
Replace YOUR_API_KEY with my API_KEY.
Open your terminal/command prompt from your project directory and run the file main.py by executing the command python main.py.
Go to your browser and type http://127.0.0.1:5000/ in the address bar.
Hurray! That's it.



How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.




