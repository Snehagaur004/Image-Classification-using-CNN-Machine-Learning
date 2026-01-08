# Image Classification using Convolutional Neural Networks
This project aims to classify the images in the given dataset as cats or dogs using convolutional neural networks(CNN)

### Approach and pipeline:
Refer to the [code](./Code) for the approach and implementation. 

### Results:
- Results after training 18,000 images of cats and dogs:
    - number of epochs = 15
    - training data / validation data split = 80/20
    - MODEL 
        - CONV 3x3 filter layers with batch norm - **32 x 64 x 96 x 96 x 64**
        - Dense layers with drop out of 0.2 and 0.3 - 256 x 128 x 2 
        - loss: 0.0638 
        - accuracy: 0.9759 
        - val_loss: 0.3255 
        - val_accuracy: 0.9044

- The model was tested on the images in the test1 folder. The performance of the model was very good and was able to predict the animals with 97-99% accuracy.

Plots for model accuracy and loss are following:
<img width="520" height="352" alt="accuracy_5000images_15epochs" src="https://github.com/user-attachments/assets/24dc0420-b938-483e-84e9-42c018712db8" />

<img width="712" height="341" alt="accuracy_18000images_15epochs" src="https://github.com/user-attachments/assets/9ca30124-67b7-4015-ad3c-027b53a115e7" />

<img width="515" height="351" alt="loss_5000images_15epochs" src="https://github.com/user-attachments/assets/7a965182-0fa8-4b3b-bec1-f17e87b564e8" />

<img width="613" height="340" alt="loss_18000images_15epochs" src="https://github.com/user-attachments/assets/585f4704-7796-43b0-b35a-d554214dc8ae" />


Classifying the images:

<img width="980" height="836" alt="dog_prediction1" src="https://github.com/user-attachments/assets/904f5833-31cf-4e8b-8f7a-44aa7c68f634" />


<img width="1008" height="792" alt="dog_prediction2" src="https://github.com/user-attachments/assets/1e73c8db-4b0b-47ba-8fc2-ef894769d9d9" />


<img width="1034" height="827" alt="cat_prediction1" src="https://github.com/user-attachments/assets/f6a12dd7-e396-4582-a9b8-8840115fd153" />


<img width="1021" height="781" alt="cat_prediction2" src="https://github.com/user-attachments/assets/1364e52b-c409-41a9-9af6-b19674385231" />




**Output video predicting the images as cats and dogs can be found here.**


https://github.com/user-attachments/assets/debddf32-dc8d-4da0-8949-d628e56c33d3




### Instructions to run the code:
[Input dataset](https://drive.google.com/file/d/19inwa0n1W4DZamjCOm5XAlztvqG_xkjP/view?usp=sharing)

- Go to directory:  _cd Code/_
- To start the training run: 
    - _$ python main.py_

    

