## Problem Statement: Detecting People Talking on the Phone

### Dataset: Collect dataset from RoboFlow website 
1.Data Collection and Annotation: I have collected a dataset from Roboflow, consisting of 2,711 images. 
 These images are annotated  : “call” for people talking on the phone and “nocall” for images without phone conversations. 
 
#### Fine-Tuning YOLOv8n Model: 
I have fine-tuned the YOLOv8n model specifically for this task using the annotated dataset.
The model is trained to detect and classify instances of people “talking on the phone” by treating it as an object detection problem.

#### Training Details: 
The model was trained for 15 epochs on Google Colab.

#### Model_prediction :
![val_batch0_pred](https://github.com/user-attachments/assets/45918fea-e103-424e-a627-7c91bd69d42d)

#### Prediction On youtube Video : This google drive link contain input and output video :
https://drive.google.com/drive/folders/1r_LTnhNfex2syz4e_wZv5yKWf-lHURq7?usp=sharing

#### Confusion Matrix:

![confusion_matrix](https://github.com/user-attachments/assets/931c42e0-bb46-4634-ad51-d7f80505777c)

#### results:
![results](https://github.com/user-attachments/assets/2cbc8680-b826-48b3-9b58-ae9141bec8fd)


### NOTE: 
Due to the resource limitations of Google Colab's free version, I initially implemented the model using YOLOv8n .
Continue refining the YOLOv8n model to enhance its detection accuracy.
I plan to further study the Florence 2 model and will work on increasing the model's accuracy.
 
