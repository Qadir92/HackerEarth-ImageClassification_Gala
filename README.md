# HackerEarth-ImageClassification_Gala
**Auto tag images taken in the gala nights on categories food, attire, decor and signage, and miscellaneous using SVC model**
***
![Accuracy in test](https://github.com/Qadir92/HackerEarth-ImageClassification_Gala/blob/main/Gala%20score.PNG?raw=true)
***

Download the dataset [here](https://www.hackerearth.com/challenges/competitive/hackerearth-deep-learning-challenge-auto-tag-images-gala/)
***
**Steps in the notebook:**
 1. Loading the data into colab notebook.
 2. Resize the training images in 3 variants:
	 a. 50x50x3 - skimage.transform
	 b. 80x60x3 - skimage.transform
	 c. 80x60 - rgb2gray
 3. Apply 95% **PCA** on the train data.
 4. Train the data on the models **GaussianNB, SVC, DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier, SGDClassifier.**
 5. Compare the performance of the models using the **accuracy score** metrics.
 6. Hyper tune the *SVC model with 80x60x3* variant of train data.
 7. Train the data on **Keras tensor flow convolution 2d** model.
 8. Make predictions with the *hyper tuned SVC* model on 95% PCA decompose test data.
***
To check out my notebook, please click [here](https://github.com/Qadir92/HackerEarth-ImageClassification_Gala/blob/main/Gala_Image_Classification.ipynb)
