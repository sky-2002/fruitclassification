# Fruit classification

### Using simpler methods like using edge features, rgb features, HOG etc with KNN.
The table below summarizes the different approaches used and accuracy obtained:<br>
|Approach|Accuracy|
|--------|--------|
|RGB features using prototype to test|35%|
|HOG using prototype to test|42%|
|KNN with HOG features|70%|

### Using comples methods like CNNs.
|Approach|Accuracy|
|--------|--------|
|CNN architecture with 3 Conv2D and 2 MaxPool|88%|
|CNN architecture in the image below|95%
![](./Designed-CNN-architecture-for-fruit-classification.png)
|CNN using altered VGG16 architecture|97%
