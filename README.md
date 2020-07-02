# Fashion MNIST Predictor

The goal is to build a Neural Network which is able to predict the following labels using python.
   0 T-shirt/top
   1 Trouser
   2 Pullover  
   3 Dress 
   4 Coat 
   5 Sandal 
   6 Shirt 
   7 Sneaker
   8 Bag 
   9 Ankle boot
 
This is done using the following libraries-
    Keras ( tensorflow in backend ).
    Matplotlib ( for plotting and analysing the data ). 
    Numpy ( for mathematical calculations and  normalising data ).
    Warnings ( I have used filterwarnings to ignore warnings and make code readable ).
    
The data has been taken from Keras MNIST dataset.
Explanation:
   1. Loading the Libraries.
   2. Loading the data and spliting it into Train and Test Data.
      ![file1](https://user-images.githubusercontent.com/48138906/86389151-85e88f00-bcb3-11ea-914a-35dadf7062cc.png)
   3. Analysing the data.
      ![file2](https://user-images.githubusercontent.com/48138906/86389318-c21bef80-bcb3-11ea-9cba-7e73944467fc.png)
   4. Normalising the data.
      ![Screenshot from 2020-07-02 22-32-06](https://user-images.githubusercontent.com/48138906/86389413-e37cdb80-bcb3-11ea-82d0-163ede9a7206.png)
   5. Importing the Sequential Models and using the Sequentail layers.      
   6. Compiling the Model and Evaluating the data.
   ![score](https://user-images.githubusercontent.com/48138906/86392143-99e2bf80-bcb8-11ea-994d-35c775bbbdb4.png)
   7. Using Plotly library to Evaluate the Prediction.
      ![fff](https://user-images.githubusercontent.com/48138906/86389617-36569300-bcb4-11ea-8a9e-51fba06c31ed.png)
   8. The accuracy score of the model is 85%.
   
The Neural Network with the layers looks like: 
  ![pppp](https://user-images.githubusercontent.com/48138906/86389760-79b10180-bcb4-11ea-988d-56c26d4d073c.png)

Activation Function
 I have used SoftMax activation function in the last layer, this activation function will give the probablity of the prediction, the label which gives the maximum probability is selected as the prediction of the row.

 In order to get better accuracy you can tweak the neural network and accordingly change the layers. The epochs ie a measure of the number of times all of the training vectors are used once to update the weights can also be increased or decreased.

A similar network can be used to update the use with more images.
