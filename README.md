Data preprocessing steps were applied with the OpenCV library, images were sized, color channels were normalized and pixel values ​​were scaled. Then, a series of operations were performed for the segmentation of the images, for example, color space transformation and k-means clustering.
The created data set is divided into training and validation data sets. This separation process is documented with tables showing class distributions. Data augmentation techniques were used for effective training and generalization of the ESA model. For example, techniques such as rescale, random rotation, width and height shifting, shear transform, zoom transform, and horizontal symmetry transform have been applied.
Basic models were created using EffiecientNetB1, MobileNet and Xception architectures. Model; Adam was compiled with RMSProp and SGD optimization algorithms, and a learning rate schedule was used to dynamically adjust the learning rate. Model training was carried out over 30 epochs.
The performance of the model was evaluated using precision, sensitivity, F1 score and accuracy metrics. Additionally, the training and validation loss graph, accuracy graph and contrast matrix were examined. The contrast matrix visualizes the classification performance of the model in detail.
![mobilenet_rmsprop1](https://github.com/user-attachments/assets/c946dd83-beeb-492d-99c3-123c818354a1)
![Figure_3](https://github.com/user-attachments/assets/8349ca8a-9cec-4dbf-96a7-854454c7a960)
![Figure_1](https://github.com/user-attachments/assets/954b2741-c63e-4de0-b1ad-2bf0be3ec143)
![eğitimkayıp1](https://github.com/user-attachments/assets/c539bdb5-5c15-43dd-8b2d-7758abc9ffd6)
![eğitimdoğruluk1](https://github.com/user-attachments/assets/1c3c913f-c767-4a9c-834c-510b3ed86dec)
