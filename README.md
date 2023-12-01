# Module-14-Challenge
In this repository you will find a .ipynb file named Machine_Learning_Trading_Bot, in this file we assume the role of a financial advisor at one of the top five financial advisory firms in the world. In recent years, my firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.
The firm is planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. Your job is to enhance the existing trading signals with machine learning algorithms that can adapt to new data.
# Part 1 Establish a Baseline Performance
Using the data provided we will use the SVC classifier model to fit the training data and make predictions based on the testing data. Review the predictions.
Review the classification report that’s associated with the SVC model predictions.
Create a predictions DataFrame that contains “Predicted”, “Actual Returns”, and “Strategy Returns” columns.
Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.

# Part 2 Tune the Baseline Trading Algorithm
In this section, I will adjust the model’s input features to find the parameters that result in the best trading outcomes. 
I will start by tuning the training algorithm by adjusting the size of the training dataset. I will then rerun the notebook with the updated parameters, and record the results.

#Question 1: What impact resulted from increasing or decreasing the training window?

#Answer:
The impact that resulted from increasing the window is a lower starting point for out returns, but as the cycle continues it becomes steady up until 2020 hits. Taking a hit from there and climbing to new heights ending at 1.6, .2 higher than our 3 Month Offset. Stating a positive correlation in cumulative return. 

![Alt text](Images/Pic1.png)






Secondly i will tune the trading algorithm by adjusting the SMA input features. Adjusting one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results. 

#Question 2: What impact resulted from increasing or decreasing either or both of the SMA windows?

#Answer:

Lastly I will choose the set of parameters that best improved the trading algorithm returns. Then i will save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document my conclusion. 

# Part 3 Evaluate a New Machine Learning Classifier
In this section, Using the original training data as the baseline model, il fit another model with the a new classifier.
I will then backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write my conclusions. 


#Question 3:  Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?

#Answer:

# Part 4 Create an Evaluation Report

To finish, il add a summary evaluation report at the end . I will express my final conclusions and analysis and i will support my findings by using the PNG images. 

#Summary Evaluation

# End of Module 14
