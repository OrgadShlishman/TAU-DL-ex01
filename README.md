# TAU-DL-ex01
Lenet5 on FashionMNIST

# About the code
Running the entire code as is will load and display the fashionMNIST data set, train and test each setting on the dataset for 10 epochs with batch sizes of 64, 
and print and save graphs of test and train accuracy for each setting. Additionally a table of final accuracies will be saved and displayed. The trained weights (model state dictionary) are saved in a .pt file by the name of the model.

Instructions for training and testing LeNet5 for a specific setting:

Run the function main(epochs,model,optimizer,model_name,loss)
Define the number of epochs, optimizer, and loss you wish to use.
 
The model and model names for each setting will be (model, model name):
LeNet5, 'Regular_Model' for the setting with no changes to lenet5
LeNet5_dropout, 'Dropout_model' for the model with dropout at the hidden layer
LeNet5_bn, 'BN_model' for the model with batch normalization
LeNet5, 'Weight_Decay_Model', and set the optimizer with weight decay for the weight decay setting

# Lenet 5 
https://www.analyticsvidhya.com/blog/2021/03/the-architecture-of-lenet-5/#h-what-is-lenet5
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/52200315-48b6-4ba8-9a97-c0a695bc2511)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/5d38a61e-2bee-4a34-927a-c13c7c727e52)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/8b4bd3eb-b802-4c3d-a728-f8f76c6cb621)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/5d973ae1-12e9-4aca-8a48-f58a4a227ca7)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/83289822-d99e-4570-ae74-d3453b9f49c4)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/90436d22-48ba-4ab9-a421-faef20248648)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/db83822b-5ccf-43fd-9b58-455cab90e89e)
![image](https://github.com/OrgadShlishman/TAU-DL-ex01/assets/128234446/1050b179-07cb-4405-8c3c-a7ab00a48354)







