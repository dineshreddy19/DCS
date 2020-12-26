# DCS
# A simple linear regression model deployed with flask & nginx wrapped in a Docker container

When you run the code /Train API is invoked and trains the model and save the file in a pickle format. For predictions I exposed /Predict API that takes the height and returns the predicted weight value.

Atthe end of final execution our flask app will be available on http://localhost:5000/

To train the model add /SimpleLinearRegression/Train and to predict the weight add /SimpleLinearRegression/Predict?height=(any value) to the above link.


