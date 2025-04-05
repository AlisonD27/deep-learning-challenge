Overview of the Analysis

    Purpose of Analysis - The purpose of this analysis was to help Alphabet Soup select the applicants for funding with the best chance of success in their ventures.

Results
  Data Pre-Processing
    1) What variable(s) are the target(s) for your model?
         * The variable from the column Is_Successful was the target for my model.
    2) What variable(s) are the features for your model?
         * The other variables used at features are as follows:  application_type, affiliation, classification, use_case, organization, income_amt, name, ask_amt. 
    3) What variable(s) should be removed from the input data because they are neither targets nor features?
          * Variables removed were:  EIN, status and special_considerations

  Compiling, Training and Evaluating the Model
    1) How many neurons, layers and activation functions did you select for your neural network model and why?
          * The first time:  110 neurons, 2 hidden layers and 1 output layer and 2 activation functions (relu and sigmoid).  The second time:  140 neurons, 3 hidden layers and 1 output layer and 2 activation functions (relu for first layer and sigmoid for the others)
    2) Were you able to achieve the target model performance?
          *  I was able to achieve 73% accuracy with the first model and 79% accuracy with the second model.  I wouldn't say that I achieved the target model performance, but it was close.
    3) What steps% did you take in your attempts to increase model performance?
          *  I eliminated more variables the second time around as well as selected more neurons and layers the second time.  It did increase accuracy to 79% from 73%.

Summary
  Overall, the model functioned pretty well, but there is room for improvement.  I did try an additional type of model (Random Forest Classifier) and while it was not as accurate as the second Neural Network Model, it was more accurate than the first Neural Network Model.    I would look at the data further to see if there were other variables that could be taken out to increase accuracy.
