Overview of the analysis: The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup that can help it select applicants for funding with the best chance of success in their ventures
Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
-The target variable is "IS_SUCCESSFUL"

What variable(s) are the features for your model?
-The other columns in our dataframe are the features in the model. The IS_SUCCESSFUL column was dropped to obtain our features cleanly.

What variable(s) should be removed from the input data because they are neither targets nor features?

-THE "EIN" and "NAME" features were removed from the input data because they are neither targets nor features.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I started high with 90 and 45 hoping to speed up the model in order to reduce loss and consider more interactions between variables. 

Were you able to achieve the target model performance?

I was able to achieve about 72% accuracy - just low from the ideal 75%.

What steps did you take in your attempts to increase model performance?

I adjusted the number of neurons hoping to speed up the model and reduce loss. I added another layer to consider more interactions between variables. I also adjusted the number of epochs hoping to achieve optimal weight coefficients.

Summary: The results of the deep learning model are that even when adjusting neurons, layers, and activation functions, the model struggled to achieve target model performance. It continued to be just short at about 72%. A different model that could be used to solve this problem is a Random Forest model because they are well suited for classification tasks
