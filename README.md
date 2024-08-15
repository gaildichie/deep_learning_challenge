
Overview of Analysis:
The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup, that can help it select applicants for funding with the best chance of success in their ventures.

Results:
Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

The target for this model is X, or all of the columns in the new_application_df, excluding the "IS_SUCCESSFUL" column.
What variable(s) are the features for your model?

The feature for this model is the y, or the "IS_SUCCESSFUL" colunn in the new_application_df.
What variable(s) should be removed from the input data because they are neither targets nor features?
The ID columns should be removed.

Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
A sequential model with 3 layers (First Hidden, Second Hidden, and Output layer), 'relu' actvation functions for each, and 80, 30, and 1 units, respectively- for the Funding notebook.
I was unable to achieve the target model performance.


What steps did you take in your attempts to increase model performance?
With my 3 attempts, I tried removing/adding columns, changing the number of units and activation type, increasing/decreasing the number of epochs, creating different bins, and choosing different cutoff values.

Summary: 
Overall, this deep learning model displays accuracy between ~ 47% to ~ 53%. Because this a large dataset with multiple varying factors, perhaps a modular neural network model would have been best to compress the data and help select applicants for funding.
