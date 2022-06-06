# Fashion Product Images Dataset: 

Brief:
The dataset mainly contains two files.
The first file includes images for clothes( shirts – shorts - ……..)
The second file includes CSV file that has some data for the images such as (color – categories – gender - ….)
The required task is to create a clothing type classifier

you can download the data from:
https://drive.google.com/file/d/1IJHl6YctfkI2MG1CH1VeHtsGiJAY8lXj/view
you can download the weigh files from:
https://drive.google.com/drive/folders/1tedU8fbxaaAgNf85fQ4pPsoxtofQMyah?usp=sharing

Data information:
Csv file size: 44424 rows × 10 columns
Images : 44242 image
Image Size: 80*60*3
used models: simple model - CNN model - Vgg16

Data preprocessing:
Filter rows
Remove article Type classes which is in article Type column that is less than 1000
No. of remained classes
10 classes remained
Split Data
20% test data
Data Generator 
16297 train -- 4074 valid -- 5094 test

First model using dense layers:
Train accuracy: 93%
Val Acc: 65%
Test acc: 64%

Second model using CNNs:
Train accuracy: 99%
Val Acc: 89%
Test acc: 90%

Third model VGG:
Train accuracy: 90%
Val Acc: 90%
Test acc: 89%

Summary :
VGG model is the best accuracy, little bit large than others but tends to give good results.
