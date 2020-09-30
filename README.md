# ImageRecognition

An image recognition project, in Google Colab.

## ball_image_recognition.py
An image recognition algorithm using the model MobileNet of Keras. It is a Google Colab app available [here](https://colab.research.google.com/drive/1v1bCRXuVSyaidh3iIl2d96i6BdmQal3W?usp=sharing)
- Input  : An image path in Google Colab
- Output : The prediction probabilities

## detectron_image_segmentation.py
An image segmentation algorithm using a pre-trained model of Facebook. It is a Google Colab app available [here](https://colab.research.google.com/drive/1FM3CKHWav-rm9hLAw5JrqWPVn1UbmhyQ?usp=sharing)
- Input  : An image path in Google Colab
- Output : The image after the segmentation with the probabilities of the detected items

## transferlearning.py
A transfer learning image recognition algorithm using a pre-trained ResNet50 model of Keras. It is changing the classification layer of the pre-trained model to a new layer, trained for the current dataset. It is a Google Colab app available [here](https://colab.research.google.com/drive/1lDQ8R8xmjG1AuPhBmORhSMsNIU8H08SY?usp=sharing)
- Input  : A path in Google Drive containing the Dataset
- Output : Stats of the Data, stats per epoch, the learning curves
