# MobileNetV2-Cifar10


https://drive.google.com/file/d/1C69xXS5WyeNjS0BHFy5DjKhcbc1FY9bw/view?usp=sharing

Andorid application which identifies Cifar10 dataset images.

## To get started we clone the TensorFlow model repository:
git clone https://github.com/tensorflow/models.git and switch to the TF-Slim models directory with cd models/research/slim.

->Next we need to define our dataset, creating a python file as description in the dataset directory, where the other dataset descriptions are arranged.


->To convert our image data to an appropriate binary file format (TFRecord) we use a script provided by Kwotsin in a Github repository(https://github.com/kwotsin/create_tfrecords).


->In next step will create TFRecord files for training and validation. With the current setting of the  validation_size parameter, 80 % of the data will be used for training and 20 % for validation. 


->To start our training we need to run  train_image_classifier.py


->The model will be automatically saved in the specified train directory
