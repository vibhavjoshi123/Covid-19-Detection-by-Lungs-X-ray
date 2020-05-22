# Covid-19-Detection-by-Lungs-X-ray
Android App for Classification and Detection of Covid-19 patients by their X-ray of Lungs

![Covid-19 Detection](https://user-images.githubusercontent.com/37294597/82539078-6a458100-9b6a-11ea-9c03-556ace8dc10f.gif)

1)First we collect data that is images of X-Ray for Normal and Covid Patients 

2)Then build a Model that can classify between Covid and Normal Based on Xray Images 

3)Convert the Model to tensorflow lite model and integrate it in Android Studio

4)Check for the images and the prediction Made

We Use Transfer Learning to build our model

We can give the new dataset to fine tune the pre-trained CNN. Consider that the new dataset is almost similar to the orginal dataset used for pre-training. Since the new dataset is similar, the same weights can be used for extracting the features from the new dataset.

If the new dataset is very small, it’s better to train only the final layers of the network to avoid overfitting, keeping all other layers fixed. So remove the final layers of the pre-trained network. Add new layers . Retrain only the new layers.

If the new dataset is very much large, retrain the whole network with initial weights from the pretrained model.

![Transfer_learning1](https://miro.medium.com/max/1400/1*9GTEzcO8KxxrfutmtsPs3Q.png)

![Transfer_learning2](https://miro.medium.com/max/1400/1*Ww3AMxZeoiB84GVSRBr4Bw.png)

