# FacialExpressionRecognition
Facial Expression Recognition, 2020spring final

Myresnet contains a model to predict the face expression. The dataset for training has the following folder request:  
training data
data_dir = '../../data/'  
train_data_dir = data_dir+'train/'  
containing
##### train_data_dir/class1/
##### train_data_dir/class2/
same request for test data.  
A .pt with trained parameter will be saved after running the MyResnet.ipynb.

To run the code in MyResnet3.ipynb, path = r'\dataset3' and fname = "\myresnet3.pt" should be altered to the local path for loading dataset and saving parameters.  

To run Model_load_predict_3.ipynb for generating video with facial expression, we need input video and pretrained model(test3.avi, myresnet3.pt both provided). Alter fname = "/myresnet3.pt" and video_path = "\test3.avi" to your local path. A ouput.mp4 will be generated at current path.

