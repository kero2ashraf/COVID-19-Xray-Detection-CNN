# COVID-19-Xray-Detection-CNN

The 2019 novel coronavirus (COVID-19) presents several unique features. While the diagnosis is confirmed using polymerase chain reaction (PCR), infected patients with pneumonia may present on chest X-ray and computed tomography (CT) images with a pattern that is only moderately characteristic for the human eye Ng, 2020. COVID-19’s rate of transmission depends on our capacity to reliably identify infected patients with a low rate of false negatives. In addition, a low rate of false positives is required to avoid further increasing the burden on the healthcare system by unnecessarily exposing patients to quarantine if that is not required. Along with proper infection control, it is evident that timely detection of the disease would enable the implementation of all the supportive care required by patients affected by COVID-19.

In late January, a Chinese team published a paper detailing the clinical and paraclinical features of COVID-19. They reported that patients present abnormalities in chest CT images with most having bilateral involvement Huang 2020. Bilateral multiple lobular and subsegmental areas of consolidation constitute the typical findings in chest CT images of intensive care unit (ICU) patients on admission Huang 2020. In comparison, non-ICU patients show bilateral ground-glass opacity and subsegmental areas of consolidation in their chest CT images Huang 2020. In these patients, later chest CT images display bilateral ground-glass opacity with resolved consolidation Huang 2020.


python packages 
1) numpy
2) pandas
3) matplotlib
4) seaborn
5) os
6) PIL
7) tensorflow
8) from tensorflow.keras.preprocessing.image import ImageDataGenerator
9) from tensorflow.keras.callbacks import EarlyStopping,ReduceLROnPlateau
10) from tensorflow.keras.models import Sequential
11) from tensorflow.keras.layers import Dense,Flatten,MaxPooling2D,Conv2D,Dropout,Activation,BatchNormalization
12) from tensorflow.keras.preprocessing import image
13) from sklearn.metrics import classification_report,confusion_matrix
os.environ['TF_CPP_MIN_LOG_LEVEL'] = '3'

questions :
1) read the train file and test file ?
2) make a image data generator to the train and test file ?
3) use an early stop and learning rate to the model?
4) train a model using CNN by filtering and max pooling three times?
5) get the model summary ?
6) get 10 epochs about the model?
7) plot using lineplot aboute val_acc and the acc?
8) plot using lineplot aboute val_loss and the loss?
9) get the final loss and accuracy for train and test?
10) get the real classes array?
11) get the predictions?
12) make a confusion matrix about real and predictions?
13) get a classification report ?
