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
