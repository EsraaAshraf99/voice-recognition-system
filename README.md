# voice-recognition-system
## Introduction
- Voice Detection an analog audio is converted into discrete signals which can be processed by different techniques to perform certain task.
- In every aspect of human life, sound plays an important role in several applications in different fields like health care which acquires the most investment Worldwide and security.Speech Recognition, also called speech-to-text, is the task of reliably converting voice data into text data. Speech Recognition is required for any application that follows voice commands or answers spoken questions. What makes speech Recognition especially challenging is the way people talk quickly, slurring words together, with varying emphasis and intonation, in different accents, and often using incorrect grammar.

## Data Set
Twenty core command words were recorded, with most speakers saying each of them five times. The core words are "Yes", "No", "Up", "Down", "Left", "Right", "On", "Off", "Stop", "Go", "Zero", "One", "Two", "Three", "Four", "Five", "Six", "Seven", "Eight", and "Nine". To help distinguish unrecognized words, there are also ten auxiliary words, which most speakers only said once. These include "Bed", "Bird", "Cat", "Dog", "Happy", "House", "Marvin", "Sheila", "Tree", and "Wow“ ,and Any other word is said and not recognized from the above words will be classified as <UNKN>.
  
## model 
  Two approaches will be used in architectures : CNN and ANN
  First :
        Artificial neural networks (ANNs), usually simply called neural networks (NNs), are computing systems inspired by the biological neural networks that constitute  animal brains.
An ANN is based on a collection of connected units or nodes called artificial neurons, which loosely model the neurons in a biological brain. Each connection, like the synapses in a biological brain, can transmit a signal to other neurons. An artificial neuron receives a signal then processes it and can signal neurons connected to it. 
The "signal" at a connection is a real number, and the output of each neuron is computed by some non-linear function of the sum of its inputs. The connections are called edges. Neurons and edges typically have a weight that adjusts as learning proceeds. The weight increases or decreases the strength of the signal at a connection.
 Neurons may have a threshold such that a signal is sent only if the aggregate signal crosses that threshold. Typically, neurons are aggregated into layers. Different layers may perform different transformations on their inputs.
 Signals travel from the first layer (the input layer), to the last layer (the output layer), possibly after traversing the layers multiple times.

Second :
        Convolutional Neural Network (CNNs)

