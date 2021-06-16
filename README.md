# Detection_and_Semantic_Segmentation_of_Low_Grade_Brain_Tumor
A Deep Learning Project using Tensorflow and Keras, to detect and semantically segment Brain Tumor(low grade glioma) from the image of a person's MRI scan.

Data:

  The data has been obtained from the Kaggle task - LGG(Lower Grade Glioma) segmentation.
  https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation

Prerequisites:

* A basic understanding of Neural Networks, CNNs, Transfer Learning, Loss functions, Metrics and Optimizers.
* Python, Numpy, Matplotlib, Pandas.
* Tensorflow, Keras
* Building, training and evaluating a Deep Learning model.


First, a customized ResNet50 model to detect Brain Tumor from a person's MRI scan image is trained and tuned.

Then, a ResUNet model to semantically segment the regions of Brain Tumor in a tumor positive scan image is built from scratch and trained.

Finally, the above two models are put together in a prediction pipeline that makes predictions and also visualizes them.


Note:
Since the project was done using Google Colaboratory, all the required packages and libraries were preinstalled.
These are the libraries and packages required,

Tensorflow, Keras, scikit-learn, scikit-image, opencv, matplotlib, plotly, seaborn, numpy, pandas, zipfile, os, glob.

The requirements.txt file from the used Colab environment is also available.




