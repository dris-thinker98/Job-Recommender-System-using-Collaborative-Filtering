# Job-Recommender-System-using-Collaborative-Filtering

## Dataset used
https://www.kaggle.com/tondji/jobs-data-for-recommender-systems <br>

## Data-Preprocessing
1. Combining data of job offers and organisation details <br>
2. Extracting job titles and their respective required skills <br>
3. Creating set of unique jobs and skills from the information extracted <br>
4. Creating meta data with jobs as rows and skills as columns for collaborative filtering <br>

## Similarity based techniques used 
1. Tanimoto or Jaccard Similarity <br>
2. Cosine or Orchini Similarity <br>
3. Distance based similarity measures: Manhattan (City Block Similarity) and Euclidean based <br>

For cosine and distance based similarity measures, we first need to vectorize the skills stored for each unique job offer and the user skillset to compare them accordingly

## Future Work
A better personalized Job Recommender System that uses the organization info and the location of the offices such that the model can filter out matching jobs that lie near the user preferred location. Also making models that utlilise other similarity measures like log-likelihood based and other deep learning infused collaborative filtering techniques for more accurate job recommendations to users.
