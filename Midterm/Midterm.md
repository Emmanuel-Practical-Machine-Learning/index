# Midterm Study Guide Spring 2021

## Short-answer questions.

### Vocabulary
- deep learning
- transfer learning
- neural net
- weights
- tensor
- (artificial) neuron
- normalize
- loss function, or cost function
- hidden layer
- fully-connected (FC)
- backpropagation
- training
- overfitting
- Hyperparameters
- Parameters
- Artificial Intelligence
- Machine Learning

## Module 1: Transfer Learning
- What is ImageNet?
- What is MobileNet?
- What are the features that MobileNet extracts from images?
- How are images stored within MobileNet? (hint: your answer should probably start with the word "As")
- When Teachable Machine "trains" -
    - what does it do to process the training image?
    - how is the image compared to the images in MobileNet?
    - what algorithm does it use to define the new classes?
- Imagine an image has been processed into a logits vector. How does Teachable Machine find similarity between this and another image? (name the algorithm)
- describe how Teachable Machine classifies an image (in use, not training)

## Module 2: Multi Layer Models
- What is a layer in a neural net?
- What kinds of behaviors change when the layer configuration changes?
- What is the purpose of an activation function?
- The Sigmoid activation function is no longer used. Why was it used in the past?
- What are weights?
- Are loss function values considered when using the network to categorize new images? Why or why not?
- Why do you separate some of your training data to NOT train on?
- A single fully-connected layer performs the same as multiple fully-connected layers, why?
- What algorithm is used to assign weights during training?
- What needs to be done to fix this model and make it valid? - have image of modelbuilder without flatten
- question about reading the train stats in MB
Module 3: Bias
Review on your notes from the A4 bias discussion 