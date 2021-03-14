data.txt format: movie-id,user-id,rating

predictions.txt format: movie-id,user-id,predicted_rating. I did not use a neighborhood here since it is a small dataset. I considered all the other movies as neighbors to a movie in making the prediction. Any negative predictions out-of-range <0 or >5, I converted to 0 and 5 respectively.

weights.txt: Similarity between every pair of movies.

means.txt format:movie, mean-rating