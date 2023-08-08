# Constrained-Neural-Network

Sparse neural network generation for MNIST, UNSW, and Audio MNIST datasets.

  1. UNSW Keras Sparsely connected.ipynb --> Sparsely connected model evaluation for UNSW dataset.
  
  2. UNSW Keras layerwise sparse .ipynb  --> An exercise to apply different sparsity at each layer.
  
  3. MNIST_Sparse_HLS.ipynb --> High level synthesis for FPGA implementation of the sparse MNIST model and compare that with non-sparse model.
  
  4. MNIST Keras two input neuron only.ipynb --> Each neuron accepts only two connections. Limiting the fan-in of the neuron and anlyzing the model performance for MNISt dataset.
  
  5. MNIST Keras Sparsely connected.ipynb --> Sparsely connected model evaluation for MNIST dataset, similar to 1.
  
  6. Audio MNIST Sparsely connected.ipynb --> Sparsely connected model evaluation for Audio MNIST dataset, similar to 5 and 1. It contain the conversion of audio samples to images and apply the convolution neural networks (CNNs) to train the model. During training, the sparsity is applied to convolution as well as the desnse layers.
  
  7. UNSW_Sparse_HLS.ipynb --> High level synthesis for FPGA implementation of the sparse UNSW model and compare that with non-sparse model, similar to 3.
  
  8. Audio_MNIST_Sparse_HLS.ipynb --> High level synthesis for FPGA implementation of the sparse Audio MNIST model, similar to 3 and 7.
  
