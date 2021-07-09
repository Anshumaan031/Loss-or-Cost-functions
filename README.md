# Loss-or-Cost-functions
LOSS FUNCTION:<br />
Loss function is a method of evaluating “how well your algorithm models your dataset”. If your predictions are totally off, your loss function will output a higher number. If they’re pretty good, it’ll output a lower number. As you tune your algorithm to try and improve your model, your loss function will tell you if you’re improving or not. ‘Loss’ helps us to understand how much the predicted value differ from actual value.<br />

Mean Absolute Error:<br />
Regression metric which measures the average magnitude of errors in a group of predictions, without considering their directions. In other words, it’s a mean of absolute differences among predictions and expected results where all individual deviations have even importance.<br />

Mean Squared Error:<br />
One of the most commonly used and firstly explained regression metrics. Average squared difference between the predictions and expected results. In other words, an alteration of MAE where instead of taking the absolute value of differences, they are squared.<br />
In MAE, the partial error values were equal to the distances between points in the coordinate system. Regarding MSE, each partial error is equivalent to the area of the square created out of the geometrical distance between the measured points. All region areas are summed up and averaged.<br />

Binary Cross Entropy Loss Function:<br />
This cost function originally stems from information theory with the transfer of bits and how much bits have been lost in the process.
Binary cross entropy measures how far away from the true value (which is either 0 or 1) the prediction is for each of the classes and then averages these class-wise errors to obtain the final loss.<br />
We can define cross entropy as the difference between two probability distributions p and q, where p is our true output and q is our estimate of this true output.
This difference is now applied to our neural networks, where it is extremely effective because of their strong usage of probability.<br />
