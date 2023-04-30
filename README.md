# NuraStyle-Final_Year_Project
NuraStyle-Final_Year_Project is a final year project **completed in 2021** that aimed to create a style transfer model that could be used on an Android app. The project used the pre-trained imagenet-vgg-verydeep-19.mat model as the base model for style transfer. This model was converted to checkpoint format and then post-training quantized and optimized to create a protocol buffer file. The protocol buffer file can be found in the .\app\src\main\assets directory of the project.

The main objective of the project was to add a manual style source and to enable the style transfer model to run on a mobile device without the need for an internet connection. This was achieved by integrating the style transfer model into an Android app and using the TensorFlow Java API to load and run the protocol buffer file on the mobile device. The app allowed the user to select a manual style source and apply it to their images using the style transfer model.


# Download
[<img src="https://user-images.githubusercontent.com/56207634/235350726-c7d993df-bfcb-4ee6-90ee-a247f72bd960.png"
     alt="Download From Releases"
     height="90">](https://github.com/UsamaKenway/NuraStyle-Final_Year_Project/releases)

# Screenshots
<img src="https://user-images.githubusercontent.com/56207634/235351714-6419ccd6-82a3-4b28-8f6e-eac4ba10b468.jpeg" width="25%" > <img src="https://user-images.githubusercontent.com/56207634/235351736-b764f652-3607-4e9a-ac92-5243f070a811.png " width="28%" > <img src="https://user-images.githubusercontent.com/56207634/235351741-4d21d054-40a1-4ddf-be5a-c39548f769c2.png" width="28%" > <img src="https://user-images.githubusercontent.com/56207634/235351747-8c3a4ff9-9cdb-42c7-a11e-d8f95b34529a.png" width="28%" > <img src="https://user-images.githubusercontent.com/56207634/235351750-ae49abeb-60b7-493d-ada6-c0f07bfe4568.png" width="28%" >

# Images Results

![Desktop_Result](https://user-images.githubusercontent.com/56207634/235352056-814bc251-2432-4dd2-8b25-b3afc826dfa0.png)


<img src="https://user-images.githubusercontent.com/56207634/235352064-737d8f6a-bc19-4938-9f03-a9f7defe03ba.png" width="40%" > <img src="https://user-images.githubusercontent.com/56207634/235352066-fc6eced0-873e-4cba-afd0-e11cf7df8d97.png" width="20%" > <img src="https://user-images.githubusercontent.com/56207634/235352067-6407c103-f2b0-4964-a16f-9ba669a0cee3.png" width="20%" >
