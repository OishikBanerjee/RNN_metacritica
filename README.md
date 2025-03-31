# README: Sentiment Analysis on Movie Reviews

## Overview
This project,`aaob055004028_rnn_metacritic.ipynb`, focuses on analyzing movie reviews using sentiment analysis. The dataset includes reviews for movies such as *La La Land* and *Pinocchio*, with each review labeled by a sentiment (positive or negative). The primary goal is to explore how different reviews and ratings correlate with sentiments.

---

## Dataset Description
The dataset consists of the following columns:

| **Column Name** | **Description**                                                                 |
|------------------|---------------------------------------------------------------------------------|
| `Movie Name`     | The title of the movie being reviewed.                                         |
| `Rating`         | Numerical rating given to the movie (scale not explicitly stated, but appears to be 1-10). |
| `Review`         | Textual review provided by the user.                                           |
| `Sentiment`      | Sentiment classification of the review (`positive` or `negative`).             |

### Sample Data
Here is an excerpt from the dataset:

| Movie Name  | Rating | Review                                                                                 | Sentiment |
|-------------|--------|---------------------------------------------------------------------------------------|-----------|
| La La Land  | 10     | Damien Chazelle’s *La La Land* is a dazzling romantic musical...                      | Positive  |
| La La Land  | 3      | I found this movie to be an insult to jazz. The music was uninspired...               | Negative  |
| Pinocchio   | 6      | Okay young Disney, even though this bombed, this version has some charm...            | Positive  |

---

## Key Features and Goals
1. **Sentiment Analysis**:
   - Classify reviews as either *positive* or *negative* based on their content.
   - Use ratings and textual data to evaluate consistency between numerical scores and sentiments.

2. **Movie-Specific Insights**:
   - Analyze trends in reviews for specific movies (e.g., *La La Land*).
   - Identify patterns in ratings and sentiments.

3. **Deep Learning Implementation**:
   - The notebook likely uses a Recurrent Neural Network (RNN) or similar deep learning model for sentiment classification.

---

## Instructions for Use
1. **Environment Setup**:
   - Ensure you have Python installed along with essential libraries such as `numpy`, `pandas`, `tensorflow`/`keras`, and `matplotlib`.

2. **Run the Notebook**:
   - Open the file in Jupyter Notebook or any compatible environment.
   - Execute the cells sequentially to preprocess data, train models, and evaluate results.

3. **Input Data**:
   - The dataset is embedded in the notebook; no additional data files are required unless specified.

4. **Output**:
   - The notebook outputs predictions for sentiment classification and visualizations of trends in ratings versus sentiments.

---

## Example Insights
- Reviews for *La La Land* show a mix of sentiments despite high ratings, indicating polarizing opinions.
- Negative sentiments often stem from personal dissatisfaction with specific aspects like music or storylines.
- Positive reviews emphasize elements like cinematography and emotional impact.

---

## Future Work
- Expand the dataset to include more movies for broader analysis.
- Experiment with advanced NLP techniques such as transformers (e.g., BERT) for improved sentiment classification.
- Incorporate additional metadata like reviewer demographics or review timestamps for deeper insights.

---

## Contact
For any questions or suggestions regarding this project, please reach out 055028@fsm.ac.in
