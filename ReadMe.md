## Visualising Hidden Layers in a convolutional neural network

Visualisation of how an input gets filtered for inference in a trained CNN network

## Getting Started

Clone the repository into the system

`git clone https://github.com/sanjeev309/cnn_heatmap.git`

Launch Jupyter Notebook and run `MNIST HeatMap.ipynb`
 

## Prerequisites

Install :
- Python 3.6 
- tensorflow
- matplotlib
- numpy

`pip3 install tensorflow==1.8.0 matplotlib numpy`
 
## Description

A CNN network is trained on the classic MNIST dataset. 

If you do not already have the dataset, the script will download it for you.

Post training, a single input image is fed again into a trained CNN network. The weights of the network post "activation"
by the convoluted image is fetched from the graph and visualised in a binary image format.
is done by the following function:
    
    getActivations(layer,stimuli,Heatmap=False)

where 
- layer :  name of the layer to visualise
- stimuli: input sample image from the mnist dataset
- Heatmap: boolean to show heatmap

 
## Results

When input of 3 is given, the first and second hidden layer's output are:

![Heatmap of Hidden Layer 1](https://github.com/sanjeev309/cnn_heatmap/blob/master/H1_layer.png)

![Heatmap of Hidden Layer 2](https://github.com/sanjeev309/cnn_heatmap/blob/master/H2_layer.png)


## Further Reading
visit Website : [AlphaDataOne](https://alphadataone.blogspot.com/2018/05/what-does-cnn-see-visualising-hidden.html) for more details.
