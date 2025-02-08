# Train-an-image-recognition-model-
by using Teachable Machine.

This Model trained to classify images into two categories:

0 → Coffee 
1 → Juice


Here is the code in details:

*Imporing the savedmodel Zip file from the Teachable Machine.
![image](https://github.com/user-attachments/assets/f872fa33-4016-4366-a578-723d7a5c365f)



*Open the Zip file to extract the files. 
![image](https://github.com/user-attachments/assets/4ee01a38-8b31-4423-b809-c2f139434878)



*To present the files and folders which are included in the default google colab directory (/content/) where files are stored when uploaded.
![image](https://github.com/user-attachments/assets/a8d3249b-0eee-4edb-bc34-e830e05bd645)



*Loading the Model.
![image](https://github.com/user-attachments/assets/bb391fdb-9f33-4508-919f-6c3f49b28dc6)



*Checking Available Signatures --->Displays the available signatures (predefined functions) in the model. that is useful to understand the input and output structure.

*Extracting the Inference Function --->Retrieves the inference function for making predictions.
![image](https://github.com/user-attachments/assets/0bcd291a-32ff-4398-aadc-a49257b7a591)



*Uploading the test picture, which is a juice.
![image](https://github.com/user-attachments/assets/1fddfd12-bac8-46c3-8f3e-b44f43753a79)



*This section preprocesses an input image before feeding it into the model for prediction.
![image](https://github.com/user-attachments/assets/082ec34f-dc41-4e1b-b112-e459544d2df2)




*This section performs model inference on the preprocessed image and extracts the predicted class. and as we can see, the class is 1 which means it is a juice. 
![image](https://github.com/user-attachments/assets/0141f771-a372-47f8-85d9-f309b135f2d0)




And here is the link of the project in google colab:
https://colab.research.google.com/drive/1EfEVqsbl2wuemtuUNcs2oErw0fepg0Oo?usp=sharing

