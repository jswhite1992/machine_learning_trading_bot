# Machine Learning Trading Bot

In this project, we aimed to improve an existing trading algorithm by incorporating Machine Learning (ML) models. The idea was to enhance the trading signals with ML algorithms that can adapt to new data. 

## Establish a Baseline Performance

We first established a baseline performance using Support Vector Machine (SVM) classifier model from sklearn's SVM learning method. Trading signals were generated using short- and long-window Simple Moving Average (SMA) values. This served as a baseline against which we compared the effects of tuning the trading algorithm.

## Tune the Baseline Trading Algorithm

Next, we tried to tune the trading algorithm by adjusting the size of the training dataset and the SMA input features. Various combinations were tried out and the set of parameters that best improved the trading algorithm returns was selected.

## Evaluate a New Machine Learning Classifier

In this section, we imported a new ML classifier (AdaBoost, DecisionTreeClassifier, or LogisticRegression), and used the original training data to evaluate its performance. The new model was backtested to evaluate its performance and compared against the baseline SVM model and the tuned trading algorithm.

## Evaluation Report

Finally, an evaluation report was created summarizing the findings of the analysis. This included discussing the performance of the different models and the impact of tuning the trading algorithm. The findings were supported using PNG images created at each step.

To reproduce the steps, open the Jupyter notebook and run the cells sequentially.
