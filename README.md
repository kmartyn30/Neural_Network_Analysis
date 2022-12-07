
# Neural_Network_Charity_Analysis
Alphabet Soup Charity

  The purpose of this project was to process the data for neutral network, test the data to predict where to make investments for loan prediction risk analysis that would be accurate and implicate the potential losses.
•	In the first neutral network model preprocessing we were to create a density plot for column values, 
•	create binds for low counts.
•	place rare categorical values in a separate column.
•	create an instance of OneHotEncoder and fit the values of the encoder.
•	merger and drop the original column for EID and Name in the DataFrame.
•	use standardize the numerical value using the StandardScaler model. 
•	create a categorized variable list.
•	process and split data into target features arrays to scale the dataset.
•	This was completed in two environments one the jupyter notebook using python until the kernel indicated were dead resulting the use of google colab python3 to process the data for neutral network. 
The overarching opitmization for this model was target proective accuracy hiher than 75% with over compile, train, and  evluation to remove features that have noisy variables by increading the nodes layers to lessen the noise. The layers are added for the multiple advantages added to the hidden layer neutral network. By restoring the previous models weight s coefficeints to try to reverse overfiltting. There is a distribution effort to find optimal weight factors. All this factors will support Alphabet Soup's team to read the 34,000 data set in the csv file to predict if the applicants were successful if funded by the team's business. 

  First steps were to read the Charity data csv file to a panda DataFrame to the variables to determine and consider the features for the targets of the model. In doing so I had to drop the EIN and name column since they were not relevant to the data and decide to use unique values, to filter the data. Next, density plot to create a column for distinctive variables in a new column and review if binning outcome. In addition, to place the data in a new DataFrame by creating a variable entity to encode one-hot conversion to merge the two DataFrames the original and the one-hot encoded DataFrame. 

Accouraging to the data set reflecting 17 application types with 2 special considerations and 2 successful out of 9 applicants who have income. 

 As you can view below the two merged DataFrames:
 <img width="1221" alt="image" src="https://user-images.githubusercontent.com/107796290/205516347-3114d9c0-dc6a-4caa-8365-a47c15576d9f.png">


In this data set $5,000 to $108,590 reflecting various loan types for each applicant. As you the Density graph implicates in the visual the application type in value counts. The density upward swing peeks at 0.00010 at 0. 

<img width="462" alt="image" src="https://user-images.githubusercontent.com/107796290/205516413-cd5550f0-336b-4070-af87-22c9af6666b4.png">

There are two additional approaches, to collapse the rare data values into “other” category. The second approach would be to provide the data points new corresponding values to classify the dataset. These two approaches are known as bucketing. This wraps up the categorical variables for the loan type. 


The table shows the results of the binning approach:

<img width="379" alt="image" src="https://user-images.githubusercontent.com/107796290/205516429-87c48c0f-8146-426c-9ace-48100d8ecc22.png">
The density plot most common unique values have more than 0 instances within the dataset. The bucket appears less than 0 times in any data set. 


Visualize the value counts of CLASSIFICATION 

One-hot encoding was to identify the unique column value to split the categorical column values. This process accelerates the memory course the data difficulty to navigate during the filtering process. This will fit our values to run the dataset. This process was to join the two data frames. 
 

The Results:

As you have reviewed several of the most common scaffold processes to organize the neutral network testing and training using bucketing and encoding as with as other techniques to demonstrate where to make investments for loan prediction risk analysis that would be accurate and implicate the potential losses.

The next process is to compile, train and evaluate the model the dataset. Basic neutral networking with several neurons to create a deeper understanding with hidden layers to deep operational changes to neural networking. This was done twice to compare the accuracy and loss of potential credit risk and investment.
 
 As we review the deep learning in the model performance metric, the model identify employees who's application is at risk approximately accuracy in the second TensorFlow, optimize yor model on order to target predictive accuracy was accuracy 0.72991251 As you can see the performance of the second test designs results are shared in the summary results. 

Summary results:

In conclusion, the prediction of application type expressed in the table below indicating the type pf appplication. In the third deliverable the model is to optimize and predict accuarcy increased over 75% by noise features by increasing the node layers 

 <img width="1277" alt="image" src="https://user-images.githubusercontent.com/107796290/205516496-4109dedc-e972-428c-965a-03eeda019064.png">
 
  The results for the network can evaluate high order nonlinear reoccurrences of the data value weight or density subsequently conducting a potential superior outcome.  The hidden nodes layers are indicated below for two node layers an outer layer. As you can see based on the compilation, train and evaluation model based on the results the overarching first optimal layer of two node's accuracy loss: 0.6065 - accuracy: 0.7285 - 500ms/epoch - 2ms/step
Loss: 0.606473982334137, Accuracy: 0.7285131216049194 which is close to the target predictive accuracy 75% however not optimized achievement. 
The second attempt wer used three layers and Epoch 5: saving model to checkpoints/weights.05.hdf5804/804 - 3s 3ms/step - loss: 0.5353 - accuracy: 0.7418 for the last 5 epoch was close however the overall Loss: 0.5975268483161926, Accuracy: 0.727580189704895
The second attempt did not meet the 75% optimization and the loss was a bit higher than the first attempt. 

<img width="574" alt="image" src="https://user-images.githubusercontent.com/107796290/205516544-f12a4856-db21-425e-831e-7b2d8e236be9.png">

  The final attempt Loss: 0.5525400042533875, Accuracy: 0.7280466556549072 target prediction, which still did not met the 75% achievment. 

 As opposed to the next compilation, train and evaluation model using several nodes and accuracy results were processed with 5 node layers. 

  The potential loss indicated 0.58... and the prediction for accuracy 0.73084... which is close to the target predictive accuracy 75% however to optimize achievement. 
 
  In comparing both models predictive accuracy and the calcuations are very similar, either model will be able to prediction the risk of the loan ore lower than 75% of the time. As you recall the logical regression model vs the neutral network are more like to overfit and can be more difficult to transform than the logical regresssion. Hoverever the neural network  can thrive in larger data set similarly to the data we have been using a predictive model across neurons due to deep learning evaulation of every interaction. In turn all three trials to compile, train and evaluate the models did not overperform the 75% accuracy, altough there were three attempts.  

