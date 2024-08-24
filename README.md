The need to create a detailed data set on B ALL cancer at the beginning of the research.
has emerged. A dataset of 3242 images regarding ALL cancer prepared at Taleqani Hospital and taken from the Kaggle platform (https://www.kaggle.com/), a public platform, was used. This set is divided into two classes: benign and malignant (Early Pre-B, Pre-B and Pro-B ALL).
Data preprocessing steps were applied with the OpenCV library, images were sized, color channels were normalized and pixel values ​​were scaled. Then, a series of operations were performed for the segmentation of the images, for example, color space transformation and k-means clustering.
The created data set is divided into training and validation data sets. This separation process is documented with tables showing class distributions. Data augmentation techniques were used for effective training and generalization of the ESA model. For example, techniques such as rescale, random rotation, width and height shifting, shear transform, zoom transform, and horizontal symmetry transform have been applied.
Basic models were created using EffiecientNetB1, MobileNet and Xception architectures. Model; Adam was compiled with RMSProp and SGD optimization algorithms, and a learning rate schedule was used to dynamically adjust the learning rate. Model training was carried out over 30 epochs.
The performance of the model was evaluated using precision, sensitivity, F1 score and accuracy metrics. Additionally, the training and validation loss graph, accuracy graph and contrast matrix were examined. The contrast matrix visualizes the classification performance of the model in detail.
