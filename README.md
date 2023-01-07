# EVA8
EVA8_Assignment_2.5


Your code MUST be:
well documented (via readme file on GitHub and comments in the code)
must mention the data representation
must mention your data generation strategy (basically the class/method you are using for random number generation)
must mention how you have combined the two inputs (basically which layer you are combining)
must mention how you are evaluating your results 
must mention "what" results you finally got and how did you evaluate your results
must mention what loss function you picked and why!
training MUST happen on the GPU
Accuracy is not really important for the SUM




Data Representation is taking MNIST data in seaparate CNN Block 
Random Integer is one hot encoded and fed to the second last layer of the model architechture


Data generation strategy is to create a random integer and store the integer and the total in the training and testing set 


Combining at the fully connected layer through concatenation , but then added another fully connected layer to store weights where network learns how to add

Cross Entropy for the block for MNIST
Mean Squared Error for the addition block 



Epoch 1: Loss = 0.1873, Accuracy = 0.9468
Epoch 2: Loss = 0.1163, Accuracy = 0.9644
Epoch 3: Loss = 0.0867, Accuracy = 0.9728
Epoch 4: Loss = 0.0786, Accuracy = 0.9751
Epoch 5: Loss = 0.0702, Accuracy = 0.9769
Epoch 6: Loss = 0.0609, Accuracy = 0.9804
Epoch 7: Loss = 0.0702, Accuracy = 0.9775
Epoch 8: Loss = 0.0484, Accuracy = 0.9829
Epoch 9: Loss = 0.0478, Accuracy = 0.9830
Epoch 10: Loss = 0.0478, Accuracy = 0.9839


