# DATA MINING AND BIG DATA ANALYTICS ASSIGNMENT
**Name**:  Poornashree S

**Class**: I-MCA-B

**Register no**: 2238m0207

**Roll no**: 22mcab26

**Topic**: Neutral Network

**Date**: 20/02/2023

## SYNOPSIS:
   
- [DATA MINING AND BIG DATA ANALYTICS ASSIGNMENT](#data-mining-and-big-data-analytics-assignment)
  - [SYNOPSIS:](#synopsis)
    - [Introduction:](#introduction)
    - [What is Neutral Network?](#what-is-neutral-network)
    - [ How Neutral Network works?](#-how-neutral-network-works)
    - [Apllication of Neutral Network](#apllication-of-neutral-network)
    - [Types of Neutral Network](#types-of-neutral-network)
    - [Recurrent Neural Network (RNN):](#recurrent-neural-network-rnn)
    - [Convolutional Neural Network:](#convolutional-neural-network)
    - [Radial Basis Function Neural Network:](#radial-basis-function-neural-network)
    - [Feed Forward Neural Network:](#feed-forward-neural-network)
    - [Modular Neural Network:](#modular-neural-network)
    - [Conclution:](#conclution)
    - [References](#references)
  
### <u>Introduction:</u>
        The neural network in data mining is a classification method that takes the input, trains itself to recognize the pattern of input data and predicts the output for new input of a similar kind. 
        Neural network forms the basis of deep learning, a subfield of machine learning that comes under artificial intelligence. Designing neural network algorithms is inspired by the structure of the human brain.

### <u>What is Neutral Network?</u>
           A neural network is a set of connected input/output units. A weight is associated with each connection, which is adjusted by the network during the learning process. So that, the network is able to predict the correct class label of input tuples.

           The artificial neural network is designed after the structure of the human brain. The structure has an input/output unit that depicts the neuron of the human brain we refer to it as a node and we refer to the connection between the nodes as a link. The figure below represents the artificial neuron network.
###   <u> How Neutral Network works?</u>       
       Knowing the overall structure of the neural network lets us understand the working of the neural network with the help of a simple example.

      Do you know how we are able to classify a flower and leaf? Consider that we see a picture of a flower which is composed of 20 x 20 pixels i.e. equal to 400 hundred pixels
      The input nodes of the network receive a set of input values. The number of input nodes is equivalent to the number of input variables.

      Now each of these pixels is fed as an input to the first layer of the neural network i.e. in our example X1 to X400.

      The first layer of the network is connected to the next layer with a link and each link is associated with a weight.

      Now, to evaluate the value for each neuron in the next layer we implement a summation function.

     Say to evaluate the value for the first neuron in the second layer of our example we would implement a summation function:

      = [X1*W11 + X3*W31]

Neural Network step 1

     This summation result is sent to the first neuron of the next layer. Now each neuron in the hidden layer has a numerical value associated with it which we refer to as ‘bias’.

    So here, the summation result is added to the bias B1.

      = [X1*W11 + X3*W31] + B1

        This result is further passed to a threshold activation function which decides whether this particular neuron will be activated or not.

     Output = Activation Function ([X1*W11 + X3*W31] + B1­)
### <u>Apllication of Neutral Network</u>
       The neural network in data mining performs the task such as:

- Classification
- Clustering or categorization
- Prediction
- Function approximation
- Optimization
- Retrieval by content or control      
### <u>Types of Neutral Network</u>
     The are several types of the neural networks depending on their behaviour they are:

- Recurrent Neural Network
- Convolution Neural Network
- Radial Basis Function Neural Network
- Feed Forward Neural Network
- Modular Neural Network  
### <u>Recurrent Neural Network (RNN):</u>
       The recurrent neural network is adapted for the data that has sequencing. The data with sequencing may be such that the one data point be depending on the previous data point. In such cases, the neural network must be modified to inntegrate the dependencies between the data points. RNN include the memory that can store the information about the previous data points that helps in generating the next output in the sequence. 
### <u>Convolutional Neural Network:</u>
       The convolutional neural network is used to recognise images and is used in the process specifically designed to process data pixels. It is a deep learning algorithm that intakes an image and assigns importance to various aspects of the image so that the network is able to differentiate one image from the other.     
### <u>Radial Basis Function Neural Network:</U>
       This kind of neural network uses a radial basis function as an activation function and it is the fastest learning network. This neural network is used for function approximation, classification and time series prediction that further helps in predicting the stock price, fraud detection in financial transactions etc.
### <U>Feed Forward Neural Network:</u>
       In this neural network, the information is propagated in the forward direction only. However, there are no cycles or loops in the data propagation. The feed-forward network is specially used for supervised learning, pattern recognition and classification, non-linear regression, and function approximation.

### <u>Modular Neural Network:</u>
       This neural network is used for solving complex AI problems. It is characterized by a series of neural networks where each neural network is independent and serves as a module in the network. Each module operates on separate input and performs a subtask from the task that the whole network is hoped to perform.

       So, this is all about the neural network in data mining that has the same structure as the human brain. Similar to the human brain the neural network takes the input process and predicts the output. Thus, it is nowadays used in much artificial intelligence (AI) systems such as face recognition, music composition, real-time translation, etc.
### <u>Conclution:</u>
       Just as the human brain is responsible for intelligence and its discriminating power, the neural network also mimics the human brain and learns from its experience and applies this learning for classification and prediction.
### <u>References</u> 
- https://binaryterms.com/neural-network-in-data-mining.html 
- https://www.investopedia.com/terms/n/neuralnetwork.asp
- https://www.javatpoint.com/artificial-neural-network               






