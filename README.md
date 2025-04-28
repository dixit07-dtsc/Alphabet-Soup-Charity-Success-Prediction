# Alphabet Soup Charity - Deep Learning
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. Using the features in the provided dataset, creating a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Instructions

1)  To execute the project follow the below commands: git clone https://github.com/dixit07-dtsc/Alphabet-Soup-Charity-Deep-Learning.git

2)  Connect google colab with the ipynb files.

3)  Install the required libraries using the following commands: !pip install -q -U keras-tuner

4) Execute the files: "AlphabetSoupCharity.ipynb" and "AlphabetSoupCharity_Optimisation.ipynb".

5) During the execution of the files, please ensure that "charity_data.csv" is selected during the uploading process of input file.

#  Summary
Based on the nature of the graphs observed (refer to Analysis Report for detailed graphs), I think that the convergence of the solution has been attained indicating that changing the number of epochs may not play a crucial role. The smoothness of the curve (loss and accuracy) may be improved by changing the other parameters such as changing the number of neurons, changing the number of hidden layers and changing the activation functions. But the overall pattern indicates that the convergence of the solution has been attained and it may be very difficult to increase the accuracy further.

#  Recommendation
A supervised machine learning can be better way to classify the groups and result. Since the number of input parameters are higher, I think a random forest classifier may provide a reliable and accurate result. Performing deep learning algorithm using random forest classifier might provide a better accuracy.

