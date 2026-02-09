# neural-craft
AIML problem statement NLP domain


The system applies strong text preprocessing and TF-IDF feature engineering, enhanced with length and word-count features. Severe class imbalance (70%) is handled using stratified sampling, class weighting, and balanced algorithms.

An ensemble approach combines Logistic Regression, Random Forest, and Gradient Boosting, with Gradient Boosting performing best overall. The final architecture uses three specialized models: Gradient Boosting for severity, Random Forest for primary category, and Gradient Boosting for secondary category.

All models run independently in a production pipeline that transforms raw text into predictions and exports results to CSV. Evaluation uses a weighted score emphasizing secondary category and severity.

note: all the notebook was made in VS Code and executed using virtual environment.
