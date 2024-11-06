# Simple-PyTorch-ANN-on-IRIS
This repo explores the impact of various neural network configurations on ternary classification performance. We experimented with a simple fully connected neural network, evaluating how different initializations (such as Xavier Uniform and Normal, He Uniform and Normal), activation functions (Sigmoid, Tanh, ReLU), and regularization techniques (Batch Normalization, Dropout) influence training stability, generalization, and overall model accuracy. By analyzing these factors, we aim to understand the effects of each choice on network behavior and performance.

This work is a collaborative Assignment as part of the _Selected Topics in AI_ course in FCAI-CU.

## Authors
- [Roaa Fathi](https://github.com/rFathi03)
- [Basma Mahmoud](https://github.com/Basma2423)

## Dataset
- We used the iris dataset from sklearn datasets synthetic ternary classification dataset with 150 samples and 4 features.
- We split them into 70% for training, 15% for validation, and 15% for testing.

## Model Architecture
- Input layer: 	4 features.
- Hidden layer: 	64 units with customizable activation functions.
- Output Layer:	03 units for ternary classification.

## Experiment Setup
### Initialization Types:
- Xavier Uniform
- Xavier Normal
- He Uniform
- He Normal

### Activation Functions:
- Sigmoid
- Tanh
- ReLU

### Configurations Tested:
- No Dropout, No Batch Normalization
- Dropout Only (rate = 0.5)
- Batch Normalization Only
- Both Batch Normalization and Dropout

### Training Parameters:
- Optimizer: 	Adam (learning rate = 0.001)
- Loss Function: 	CrossEntropyLoss
- Epochs:		10 per configuration
- Seed			42

## Results
![image](https://github.com/user-attachments/assets/eaa32b8a-85e0-4b89-9ec2-145f6b79a4eb)


## Plotting
1. **Xavier Uniform and Sigmoid**
![image](https://github.com/user-attachments/assets/8346741d-20c1-451a-a28d-313ffae9d0f0)
2. **Xavier Uniform and Tanh**
 ![image](https://github.com/user-attachments/assets/e6ef6215-f1af-4e2c-997d-1a35751d3ae3)
3. **Xavier Uniform and ReLU** 
![image](https://github.com/user-attachments/assets/f1afc691-690f-4503-a6bc-951e8e9b4e93)
4. **Xavier Normal and Sigmoid**
 ![image](https://github.com/user-attachments/assets/30b632eb-f63c-4707-8e32-1b20e8129d30)
5. **Xavier Normal and Tanh**
![image](https://github.com/user-attachments/assets/b86b4283-7294-4e05-b0a9-9983e4d719c4)
6. **Xavier Normal and ReLU** 
![image](https://github.com/user-attachments/assets/0131e5b6-30ea-4fa9-b5a3-b55f3ca1b0ad)
7. **He Uniform and Sigmoid**
![image](https://github.com/user-attachments/assets/fab83965-3397-4bb6-a4cd-e7fe9c4e2b8f)
8. **He Uniform and Tanh**
![image](https://github.com/user-attachments/assets/f7d7d3e5-c345-4881-b9af-47305d3462cb)
9. **He Uniform and ReLU** 
![image](https://github.com/user-attachments/assets/e749d6a0-bb8a-41d2-af98-8b632ae69926)
10. **He Normal and Sigmoid**
![image](https://github.com/user-attachments/assets/1f81079c-135b-4260-9b1d-7959ccbd4831)
11. **He Normal and Tanh**
 ![image](https://github.com/user-attachments/assets/9891e2c5-4803-48ee-8de6-3bcb5c370a9a)
12. **He Normal and ReLU** 
![image](https://github.com/user-attachments/assets/8499b2f6-1e8a-4430-8b1b-acc011371f85)












