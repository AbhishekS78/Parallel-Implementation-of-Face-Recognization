# Parallel-Implementation-of-Face-Recognization
A parallel implementation of the LBPH algorithm for face recognition is developed and studied. Later a parallel implementation has been developed using the OpenMP API. 
## Project Name:
Parallel Implementation of Face Recognization
## Project Description:
In computer science, face recognition is basically the task of recognizing a person based on its facial image. Face recognization can be defined as, 'The face recognition algorithm is in charge of figuring out the features that best define the image once the facial images have been extracted, cropped, resized, and usually converted to grayscale'. 

The algorithm than we will be using for our project is [Local Binary Patterns Histograms (LBPH)](https://en.wikipedia.org/wiki/Local_binary_patterns). 

- ### Local Binary Patterns: 
LBP is a simple yet very effective texture operator that identifies each pixel in an image by thresholding its surroundings and treating the result as a binary number.  It has further been determined that when LBP is combined with histograms of oriented gradients (HOG) descriptor, it improves the detection performance considerably on some datasets. Using the LBP combined with histograms we can represent the face images with a simple data vector.

## Project Workflow:
- Parameters setup: setting up the four parameters which are radius, neighbour, grid X, and grid Y.
- Training the algorithm and applying LBP operation
- Extracting the histograms from pixels
- Performing face recognization
- Developing parallel implementation using OpenMP API

## Code:
The coding has been done in C++ language on VS Studio. The files for the project has been uploaded on [Github repository](https://github.com/AbhishekS78/Parallel-Implementation-of-Facial-Recognization).
