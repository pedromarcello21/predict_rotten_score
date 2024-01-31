# Pedro Vincenty

## Movie Rating Prediction Model

### Overview
In this project, I extended the work from my web analytics course at Fordham, where I developed a program to scrape ratings and reviews from 100 movies on Rotten Tomatoes. The goal was to build a predictive model for a movie's ratings based on its reviews. Using a count vectorizer classifier with unigrams and bypassing English stop words, I achieved an impressive accuracy of 99.36%.

Link to download 100 movie reviews and ratings: [# predict_rotten_score](https://drive.google.com/file/d/1IgznTPo0OY_bZviQD-zj8jrcyVqPIC-C/view)https://drive.google.com/file/d/1IgznTPo0OY_bZviQD-zj8jrcyVqPIC-C/view

### Model Evaluation
To validate the model, I selected Martin Scorsese's movie "Silence" and collected 5 pages of reviews. These reviews were processed through the same count vectorizer, and the model predicted the ratings with an accuracy of 89%. While this accuracy is noteworthy, it's essential to identify instances where the model failed.

### Incorrect Predictions
The following data frame displays the first 10 records where the model incorrectly predicted the movie rating:

| Review                                               | Rating | Prediction |
|------------------------------------------------------|--------|------------|
| Silence is an example that with passion a film…       | 1      | 0          |
| It’s not quite the “priestsploitation" nonsens...    | 0      | 1          |
| Silence is a dreadful film from beginning to end.     | 0      | 1          |
| The film completes what would be Scorsese's sp...    | 1      | 0          |
| Its complex message about faith and the faithf...    | 0      | 1          |
| Basically, Silence looks and sounds great. But...    | 0      | 1          |
| Even at its unnecessary length, Silence is sel...    | 1      | 0          |
| By the end of the ordeal, the question is stal...    | 0      | 1          |
| An ambitious tape that limps at times. However...    | 1      | 0          |
| As one of the unarguable geniuses of American ...    | 0      | 1          |

### Prediction Accuracy Bar Graph
The bar graph below illustrates the prediction accuracy of the model based on the number of predictions made. This visualization provides insights into the model's performance across various instances.

[Insert Bar Graph Image Here]

### Conclusion
While the model achieved high accuracy in general, the mispredictions on specific reviews for "Silence" highlight potential areas for improvement. Further refinement of the model, perhaps through feature engineering or exploring different natural language processing techniques, could enhance its predictive capabilities.

Feel free to explore the code and additional details in the attached files to gain a deeper understanding of the methodology and results.


