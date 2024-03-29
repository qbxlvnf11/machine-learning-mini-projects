
Description
=============

#### - Basic machine learning model
#### - Upload code as a Jupiter Notebook file (.ipynb) for immediate understanding


Contents
=============

#### - Comparison between Decision Tree and Random Forest: [Comparison_decision_tree_random_forest.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Comparison_decision_tree_random_forest.ipynb)
#### - K-NN Classifier and Regressor: [K-NN_Classifier_Regressor.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/K-NN_Classifier_Regressor.ipynb)
#### - Pytorch implement of backpropagation algorithm with MLP: [Pytorch_Backpropagation.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Pytorch_Backpropagation.ipynb)
  - Backpropagation algorithm: https://blog.naver.com/qbxlvnf11/222640241085
  - Code description: https://blog.naver.com/qbxlvnf11/222649122193
#### - Solving Regression Problem (Prediction of Fuel Efficiency): [Regression_fuel_efficiency.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Regression_fuel_efficiency.ipynb)
#### - MNIST, CIFAR-10 Image Classifier with Multi Class ROC Curve: [Image_classifier_MNIST_CIFAR10.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Image_classifier_MNIST_CIFAR10.ipynb)
#### - Recurrent Convolution News Classifier with Character Embedding: [News_classifier_recurrent_convolution.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/News_classifier_recurrent_convolution.ipynb)
#### - Bidirectional LSTM News Classifier with Character Embedding: [News_classifier_bidirectional_LSTM.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/News_classifier_bidirectional_LSTM.ipynb)
#### - Charcter-level Featrue and Word-level Feature t-SNE: [Character-level_Word-level_t-SNE.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Character-level_Word-level_t-SNE.ipynb)
#### - Driving behavior classification with ConvLSTM2D: [Driving_behavior_classification_ConvLSTM2D.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Driving_behavior_classification_ConvLSTM2D.ipynb)
#### - Hand gesture recognition with CNNs: [Hand_gesture_recognition.ipynb](https://github.com/qbxlvnf11/machine-learning-basic/blob/master/Hand_gesture_recognition.ipynb)

Datasets
=============

#### - News Aggregater

https://www.kaggle.com/uciml/news-aggregator-dataset

#### - Pima Indians Diabetes

https://www.kaggle.com/uciml/pima-indians-diabetes-database

#### - Auto MPG

https://archive.ics.uci.edu/ml/datasets/auto+mpg

#### - Driving Behavior 

https://www.kaggle.com/datasets/outofskills/driving-behavior

#### - Hand Gesture Recognition

https://www.kaggle.com/datasets/aryarishabh/hand-gesture-recognition-dataset

References
=============

#### - CIFAR10 Classifier

https://appliedmachinelearning.blog/2018/03/24/achieving-90-accuracy-in-object-recognition-task-on-cifar-10-dataset-with-keras-convolutional-neural-networks/

#### - Multi-class ROC Curve

https://scikit-learn.org/stable/auto_examples/model_selection/plot_roc.html

#### - Sequence Data Classifier

https://tykimos.github.io/2017/08/17/Text_Input_Binary_Classification_Model_Recipe/

#### - K-NN

https://subinium.github.io/MLwithPython-2-3-1/

#### - t-SNE

https://www.kaggle.com/eliotbarr/news-exploration

#### - Confusion Matrix Visualization

https://scikit-learn.org/stable/auto_examples/model_selection/plot_confusion_matrix.html

#### - Regression Problem

https://www.tensorflow.org/tutorials/keras/regression?hl=ko

#### - Driving Behavior Classifier: ConvLSTM2D

https://www.kaggle.com/code/outofskills/binary-conv-lstm

Erratum of Jupyter Notebook Files
=============

#### - News_classifier_recurrent_convolution.ipynb

[29] block: 

y_train = np.expand_dims(X_train, -1) -> y_train = np.expand_dims(y_train, -1)

y_test = np.expand_dims(X_test, -1) -> y_test = np.expand_dims(y_test, -1)

#### - News_classifier_bidirectional_LSTM.ipynb

[29] block: 

y_train = np.expand_dims(X_train, -1) -> y_train = np.expand_dims(y_train, -1)

y_test = np.expand_dims(X_test, -1) -> y_test = np.expand_dims(y_test, -1)

Author
=============

#### - LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

#### - Blog URL: https://blog.naver.com/qbxlvnf11

#### - Email: qbxlvnf11@google.com, qbxlvnf11@naver.com
