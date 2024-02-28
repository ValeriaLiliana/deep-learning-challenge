# deep-learning-challenge

OVERVIEW
This deep learning model, developed for the nonprofit organization Alphabet Soup, aims to assess the success of its fund applicants. Alphabet Soup supplied a dataset comprising information on over 34,000 businesses and organizations, including details on the applicants' financial status, the amount of funding provided by Alphabet Soup, and other relevant factors. Essentially, the model is crafted to forecast whether the financial support from Alphabet Soup contributes to the success of the applicants. However, Alphabet Soup has set a requirement that the model must achieve a minimum accuracy of 75% before considering its deployment for their internal use, despite their initial enthusiasm.

DATA PROCESSING 
-Target Variable(s): The model's target was a binary variable signifying the success or failure of the organization in its pursuits.

-Feature Variable(s): The model incorporated diverse characteristics of the organizations as its features, encompassing attributes such as organization type, income amount, application type, and others. These features were considered after undergoing preprocessing.

-Variables Removed: The EIN and NAME columns were excluded from the dataset since they serve as identifiers and do not impart any predictive value to the model regarding organizational success.



COMPILING, TRAINING AND EVALUATING THE MODEL
Neurons, Layers, and Activation Functions: The neural network model was structured with multiple layers, comprising input, hidden, and output layers. The initial hidden layer featured a substantial number of neurons employing a relu activation function to capture intricate non-linear relationships within the data. A secondary hidden layer was introduced to enhance the model's complexity, potentially augmenting its predictive capabilities. The output layer utilized a sigmoid activation function, particularly suitable for binary classification tasks.

Model Performance: The model demonstrated a loss of 0.5588 and an accuracy of 0.7280. While the accuracy surpasses 70%, there remains an opportunity for enhancement to meet the targeted predictive accuracy of over 75%.

Optimization Efforts: In pursuit of heightened model performance, various strategies were explored. These included adjusting the number of neurons in the layers, introducing additional hidden layers, experimenting with diverse activation functions, and modifying the number of epochs in the training process.

SUMMARY
The deep learning model created for Alphabet Soup exhibited a notable capability in forecasting the success of funded organizations, achieving an accuracy rate of 72%. Despite its commendable performance, it fell short of reaching the desired target accuracy surpassing 75%.
