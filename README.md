Emotional Facial Expression Recognition Model

### The [KDEF](https://kdef.se/) dataset

- The model used was CNN, using the pretrained InceptionV3-BiLSTM
  

<img width="999" alt="image" src="https://github.com/user-attachments/assets/08350a6e-9e17-496f-9280-1e9904a24889" />


- The training accuracy plot:

![image](https://github.com/user-attachments/assets/ede007ec-406e-4a7d-9620-09bae65812b4)

The training loss plot

![image](https://github.com/user-attachments/assets/e77f1a47-ee88-48ad-a5b0-84c754346a5b)



- The model performance:

<img width="999" alt="image" src="https://github.com/user-attachments/assets/6e3be42f-1698-4d3b-a314-d9a6a48eeb37" />


- The confusion matrix:

<img width="882" alt="image" src="https://github.com/user-attachments/assets/da3aa3f8-b463-4a4a-9f60-a1381f5974c5" />


- Comparative models:
  ![image](https://github.com/user-attachments/assets/2398f202-edb6-40ed-baf9-073d6b2ccce6)

### Libraries

Putting pictures in Pandas dataframes, along with theirData Frame and:

Importing FIles:
- Imutils 
- os
- glob 
- PIL 
- cv2

Data preparation:
- Pandas: Reading the labels from the CSV files
- Numpy: Craeting a Numpy array of the images with their associated label matched from the tables in the CSV file, ready-to-use for the machine learning model
- TensorFlow

Model devopment:
- Keras
- scikit-learn

Visualisation:
- matplotlib.pyplot
- tqdm


