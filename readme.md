<h2> MULTIMODAL DEEP LEARNING  - TENSORFLOW / KERAS</h2>

### Paper presented at DLDC 2021  [DLDC_2021_Camera Ready Version_Bharath_Sabeesh.pdf](https://github.com/sabeesh90/Multimodal_Deep_Learning/files/7781427/DLDC_2021_Camera.Ready.Version_Bharath_Sabeesh.pdf)


This repository contains code pertaining to multimodal deep learning classification performed on the SDSS-4 DR-16 dataset with a SOTA accuracy of 99%. The Sloan Digital Sky Survey captures spectroscopic and photmetric information about the various astronomical bodies such as galaxies, stars and quasars. The dataset consists of both tabular and image data which have been downloaded from the SDSS website. http://skyserver.sdss.org/dr16/en/tools/search/sql.aspx. There are 6 features and 1 target variable for the tabular data. The target variable is a 3 class variable. There are a total of 1000 datapoints. The distribution of the images along with the images of the astronomical bodies (Galaxies, stars and Quasars - In order) is shown below.

<img src="https://user-images.githubusercontent.com/48343095/147462673-6c286301-d149-4e4e-8351-27bea0873045.png" width="900"  height = "250"/>
<img src="https://user-images.githubusercontent.com/48343095/147392939-e01a5375-8161-460a-89de-3ab4fbff5a59.png" width="300"  height = "250"/>

<h2> CONVENTIONAL MACHINE LEARNING</h2>
Machine learning models have been built using scikit learn library and the pycaret distribution. Tree based classifiers and Gradient Boosting algorithms show higher evaluation metrics than other algorithms but however their performance on class imbalance was not satisfactory. ANNS show better performance on class imbalance and even have higher model metrics. These deep networks are superior to other ML architectures on tabular data. 
<img src="https://user-images.githubusercontent.com/48343095/147462826-0955d7a5-db0a-4726-8d2b-75de0df6f597.png" width="450"  height = "350"/>

<h2> UNIMODAL DEEP LEARNING</h2>
<img src="https://user-images.githubusercontent.com/48343095/147462655-5f932468-60a6-4b55-84c2-f3c24a14a77e.png" width="400"  height = "180"/>
<img src="https://user-images.githubusercontent.com/48343095/147473706-df38cd1d-5fce-4fee-a83b-be30d8827408.png" width="400"  height = "180"/>
The following were  observed on unimodal deep learning algorithms
1) Newer architecture better than older architectures on ‘minimal fine tuning’ <br>
2) Overfitting / underfitting on older architectures<br>
3) Steeper curve<br>
4) No significant train test gap Higher Evaluation metrics<br>
5) Higher Accuracies in minimal epochs<br>
The class wise scores however showed a decline in the Quasar class
<img src="https://user-images.githubusercontent.com/48343095/147473922-33e2db96-6412-4e8e-a853-0c9a57538d6c.png" width="400"  height = "180"/>

<h2> MULTIMODAL DEEP LEARNING </h2>
Multimodal deep network has been built by combining tabular data and image data using the functional API of keras.
The following was inferred.
<img src="https://user-images.githubusercontent.com/48343095/147474493-5aabe461-bbce-4f9d-a38e-32d835bdc73c.png" width="400"  height = "150"/>
The class wise metrics were aso superior in mnultimodal deep learning with no effect of class imbalance on the model performance.
<img src="https://user-images.githubusercontent.com/48343095/147474352-ee2134c6-e6d8-4caf-9c0b-f0182326605b.png" width="400"  height = "150"/>
The following are the findings of the architecture <br>
1) Curves of even older architectures improves in multimodality <br>
2) EfficientNetB2 and Xception has steepest curves  - (better than unimodal deep learning) <br>
3) Highest accuracies at minimal  number of epochs (better than unimodal deep learning) <br>
4) Perfectly fitting model – Train test gap – least <br>

<h2> TRAINING CURVES </h2>
The training curves below show that the multimodal curves show better fitting than the unimodal curves.

![unimodal dl](https://user-images.githubusercontent.com/48343095/147476061-aebc2bcb-307f-4bab-889e-75b73e23b428.png)
![mm dl](https://user-images.githubusercontent.com/48343095/147476073-bc9a31d9-cc24-4580-936f-fa383e95b097.png)

<h2> SOTA ACCURACY </h2>
We were able to achieve a SOTA accuracy of 99% on this dataset using multimodal deep learning. Similar SOTA results were also obtained using Customized CNN. The details of the same are in the Colab Notebook link provided in this repository. the findings were published in the DLDC Summit - 2021 as a part of the publication in the Lattice journal

  
