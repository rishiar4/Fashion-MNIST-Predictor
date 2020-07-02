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
   
   ![file1](https://user-images.githubusercontent.com/48138906/86393072-1c1fb380-bcba-11ea-9f61-72a225aa2c07.png)
   
   3. Analysing the data 
   
   ![file2](https://user-images.githubusercontent.com/48138906/86393192-4f624280-bcba-11ea-9f10-0f6e922e5e6f.png)
   
   ![Screenshot from 2020-07-02 22-32-06](https://user-images.githubusercontent.com/48138906/86393752-1f676f00-bcbb-11ea-97fe-9387a3a6c043.png)

   4. Normalising the data.
   
   5. Importing the Sequential Models and using the Sequentail layers.
   6. Compiling the Model and Evaluating the data.
   7. Using Plotly library to Evaluate the Prediction.
     ![fff](https://user-images.githubusercontent.com/48138906/86393609-f0e99400-bcba-11ea-88eb-f89da0b91d7b.png)
   8. The accuracy score of the model is 85%.
   
   
     ![score](https://user-images.githubusercontent.com/48138906/86393692-08288180-bcbb-11ea-8586-0247fda6a3fe.png)

   9. The Neural Network with the layers looks like: 
   
   
      ![pppp](https://user-images.githubusercontent.com/48138906/86393563-e0391e00-bcba-11ea-83bd-c1b6332c4469.png)
      
      
   Activation Function
 I have used SoftMax activation function in the last layer, this activation function will give the probablity of the prediction, the label which gives the maximum probability is selected as the prediction of the row.

 In order to get better accuracy you can tweak the neural network and accordingly change the layers. The epochs ie a measure of the number of times all of the training vectors are used once to update the weights can also be increased or decreased.

A similar network can be used to update the use with more images.

   
