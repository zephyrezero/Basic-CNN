# Basic-CNN
Well this is a basic Convolutional Neural network trained using Mnist data set 
# Requiremnets
* Python 3.xx (interactive mode)
* tensorflow  
* matplotlib
### Or
* Colaboratory By Google

# Process
 Import Tensorflow and Mnist dataset keras to start building the model
* load data into X and Y
* for intial data visualiztaion use plt.imshow
* use normalize function to scale the values between 0 and 1
* create a model (defining type of model 'sequential')
* flatten the model
* create 2 Dense layer with 128 neurons (act=relu)
* a final output layer (act=softmax)
* compile the model (optimizer,loss,metrics)
* fit the model with number of epochs
* model.evaluate assign loss and acuuracy
* save the model using the save function
* save it with .h5 exeten (saves the model in hierarchial data format rather than .pb format as .pb is default extension of tf)

# Genreal Plot
![download](https://github.com/zephyrezero/Basic-CNN/assets/147026858/b4583e52-396c-4f56-bc8c-bb11c1406cc5)


