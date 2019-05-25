Python Projects for Computer Vision with TensorFlow

# AS4: TensorFlow Estimator Code Sample
You will find in AS4 directory a python script tf_sample_cnn.py. 
This script is a simple implement of a 2 layer CNN using TensorFlow Estimator API.
The CNN model is trained on the MNIST dataset for 5 epochs. 
Evaluation of the model is done every epoch.

There are few other things that the script does such as:
1. Distributed training on all available GPUs. See line 317 and 204
2. Uses TensorBoard naming convention for visualizing the model's graph
3. Uses tf.summary() to save and visualize input images, histograms, and scalar plots of metrics such as accuracy and loss

# Run Script Instruction
Dependencies: You should have the latest version(v11.1.0) of tensorflow/tensorflow-gpu installed.

To run the script use command: python tf_sample_cnn.py

