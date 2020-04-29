# DcFlow
DcFlow: Optical FLow via Cost Volume Processing

We present an optical flow estimation algorithm described in Accurate Optical Flow via Direct Cost Volume Processing. The project can be divided into two part. The first part describes how to generate feature embedding via a convolutional neural network. The second part is how the 4-dimensional cost volume can be efficiently constructed and stored using the embedding. We conduct experiments on Sintel benchmark to evaluate the cost volume with a winner-take-all matching algorithm. We also show that adding a normalization layer to the CNN model outperforms the original model.
