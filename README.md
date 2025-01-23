# DataAugmentation CIFAR10 PYTORCH 🤖
# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;"> DataSet Discription</p>

**The CIFAR-10 dataset comprises 60,000 32x32 color images categorized into 10 classes, with each class having 6,000 images. Among these, 50,000 images are for training and 10,000 for testing, maintaining the original split. The dataset includes:**
* * train.7z: A folder with training images in PNG format.
* * test.7z: A folder with test images in PNG format.
* * trainLabels.csv: File containing training labels.

**To prevent cheating, 290,000 "junk" images were added to the test set, disregarded during scoring. Also, slight modifications were made to the original 10,000 test images to prevent identification via file hash. These alterations should not significantly affect scoring. Predictions are required for all 300,000 images. The classes include:**

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

**Classes are mutually exclusive with no overlap; for instance, "automobile" encompasses sedans and SUVs, while "truck" refers to large trucks excluding pickups**



# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;">About me </p>

### ***👋 Greetings, all! I'm <strong>Mohsin Saleem<strong>, a data scientist that is interested about mastering <strong>machine learning<strong> techniques and continually extending his expertise. I believe in the mindset of continuous learning and support because I am dedicated to the continued development and support of others in the profession***
##  <span style="color: #EEBB6D;"></span> <span style="color: orange; font-weight: bold;"> Connect with me :</span>
[![GitHub](https://img.shields.io/badge/GitHub-Profile-blue?style=for-the-badge&logo=github)](https://github.com/Mohsin-Sial099) 

[![Kaggle](https://img.shields.io/badge/Kaggle-Profile-blue?style=for-the-badge&logo=kaggle)](https://www.kaggle.com/mohsinsial) 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mohsinsial/)


# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;">Dataset Transformation</p>

**I did Applied random cropping, horizontal flipping, tensor conversion, and normalization with provided statistics to prepare training and validation sets for CIFAR10**



# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;">Training PyTorch DataLoader"</p>

**In order to improve performance, I have used the DataLoader from PyTorch for a more efficient handling of training and validation data, as well as movement and concurrent loading.**


# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;">Device Assignment </p>

**In order to ensure that PyTorch runs efficiently on available hardware, I've defined functions for checking and assigning the correct deviceCPU or GPU To run CiFAR10 dataset**


# <p style="font-family:Algerian;font-size:150%;text-align:center;color:#0F18BA;">Applying Simple ResNet</p>

**I did Utilized a custom SimpleResidualBlock model on the CIFAR-10 dataset, verifying output shapes for a single batch, optimizing memory usage by releasing variables and clearing CUDA cache**

# Final
