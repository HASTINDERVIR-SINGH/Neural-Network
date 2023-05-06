# Neural Network Project
Neural Network respository

In this repository I have shared on some of the things and projects I have worked on, these are all focued around the CNN (Convutional Neural Network) and its different
varaition used by everyone in general.




# Abstract
This notebook contains the code that identify and differntiate the clothing picutre in fashion mnist dataset. The dataset contain of 70,000 black and white images, which are in 28*28 grayscale image format, associated with a label from different 20 classes.

In the code below we are going to use CNNs to identify and correctly predict the images class along with it's scategory. The observation are both visual and statistical are made before models, to understand more about the data. A variety of histogram and scatter plot are made.

Hence the data is prepared differently for each model. The first 2 model are CNN but they have different model layer and droup out and the third DCSCAN is used for creating fake batch so that if their is any need to share the data some fake images are present. Out of the two cnn model the second model is better in predicting images along with its predictibility.

The  dataset and the code is helpful for identifying for fashion category so that it can be used in online shop for adding new styles in category for  shop or identifying the shirt and other clothes which are present online.

The dataset can be found on kaggle website from the link: https://www.kaggle.com/datasets/zalando-research/fashionmnist?select=t10k-labels-idx1-ubyte

# Analysis and Visualization

### Importing different libraries required for this project
![image](https://user-images.githubusercontent.com/78008979/236595194-ce0c99f1-02d2-452c-9d8f-39a061ec9c48.png)

- This section is for showing what the fashion-mnist dataset looks like with each picture divided into a 28*28 grayscale format for better understanding for the array in a csv file
![image](https://user-images.githubusercontent.com/78008979/236595628-be3c72ae-e850-4f69-84d5-99f100c8acaf.png)

- Then printing the output to check the number of rows and cloumns in the dataset from both the test and train data files. Additionally we would also check the infornation about our data with pandas 'dataframe.info()' funtion
![image](https://user-images.githubusercontent.com/78008979/236595715-48c3d733-9566-4df6-b245-ad44c090d492.png)
Here we can observe that train data set has rows:  60000  and  columns:  785 and our test dataset has rows:  10000  and columns: 785.

Also from information we can check the index range, columns, column names omly of start and the end, the datatype we are using to see it's format. 

- For the next step we gpoing to analyse the specific detail such as min, max, std and mean from the data.
![image](https://user-images.githubusercontent.com/78008979/236596131-43915bac-480d-46f8-ac93-2440cd4afc08.png)

- We are also going to see the correaltion coefficient for each column with column.
![image](https://user-images.githubusercontent.com/78008979/236596186-e31ff0fb-a570-49e8-82eb-48a8bf7dc84f.png)


going to complete the rest 
