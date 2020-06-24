# Springboard Capstone Project 2

<img width="959" alt="Screen Shot 2020-05-31 at 1 08 31 PM" src="https://user-images.githubusercontent.com/55601793/83361734-2c054a00-a340-11ea-82cc-a61474dad4b9.png">

In this project, I applied CNN which was built from scratch and transfer learning using VGG16 to the binary classification problem of determining which of two classes ‘ normal’ or ‘pneumonia’ a chest x-ray falls under.  First, I applied both of the models to the original x-ray images. The number of images in ‘normal’ class was around 1300 and the number of images in ’pneumonia’ class was around 3800. To balance the number of images in each class, I used an adapted DCGAN model to generate more images to be added to the dataset. Then I applied both of the models to the new dataset which included both original and generated images. All of the applications achieved around 90% accuracy on the test set. 

The dataset is obtained from [www.kaggle.com](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia). For more in-depth information about my project please refer to the links below.

1. [Project Reports](https://github.com/Meralbalik/Capstone-Project-2/blob/master/Capstone%20Project%202%20Proposal.pdf)
2. [CNN with original images](https://github.com/Meralbalik/Capstone-Project-2/blob/master/CNN_with_original_images.ipynb)
3. [VGG16 with original images](https://github.com/Meralbalik/Capstone-Project-2/blob/master/VGG16_with_original_images.ipynb)
4. [DCGAN to generate images](https://github.com/Meralbalik/Capstone-Project-2/blob/master/DCGAN_ChestXRay_Pneumonia.ipynb)
5. [CNN with generated images](https://github.com/Meralbalik/Capstone-Project-2/blob/master/CNN_with_generated_images.ipynb)
6. [VGG16 with generated images](https://github.com/Meralbalik/Capstone-Project-2/blob/master/VGG16_with_generated_images.ipynb)
7. [Project Presentation](https://github.com/Meralbalik/Capstone-Project-2/blob/master/Reports/CapstoneProject2Presentation.pdf)
