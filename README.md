# Deep-Learning-Challenge
## Introduction
  In the context of the Deep Learning Challenge, I have undertaken several attempts to construct a neural network model capable of accurately predicting outcomes based on the provided dataset. Our primary objective was to achieve an     accuracy rate of 75% or higher in our predictions. This README file summarizes the three attempts made, presenting key information such as loss values, accuracy, and potential enhancements for future endeavors.

* Attempt #1
In the first attempt, the following configuration was employed:

  * APPLICATION_TYPE cutoff: 528
  * CLASSIFICATION cutoff: 1883
  * Layer 1: 80 neurons with a ReLU activation function
  * Layer 2: 30 neurons with a ReLU activation function
* Results:

  * Loss: 0.5556
  * Accuracy: 72.87%
  * Observations:

The loss value suggests room for further optimization.
The achieved accuracy of 72.87% falls short of our 75% target.
* Attempt #2 (Most Optimized)
  The second attempt involved adjustments to the cutoff values while keeping the neural network architecture consistent with Attempt #1:

  * APPLICATION_TYPE cutoff: 66
  * CLASSIFICATION cutoff: 95
* Results:

  * Loss: 0.5586
  * Accuracy: 73.27%
  * Observations:

  Despite alterations in the cutoff values, significant performance improvement was not observed.
  Accuracy remained below the desired 75%.
* Attempt #3
  For the third attempt, modifications were made to the neural network architecture while retaining the initial cutoff values:

  * Layer 1: 88 neurons with a ReLU activation function
  * Layer 2: 44 neurons with a tanh activation function
  * Layer 3: 22 neurons with a ReLU activation function
* Results:

  * Loss: 0.5639
  * Accuracy: 72.88%
  * Observations:

  Once again, the model's performance did not reach the 75% accuracy threshold.
  Changes in the neural network architecture did not yield the desired improvement.
* Conclusion and Recommendations
  In summary, my first attempt achieved an accuracy of 72.87%. Despite different cutoff values in the second attempt, only a slight improvement to 73.27% was observed. The third attempt, which involved altering the model's structure,   achieved an accuracy of 72.88%. While progress has been made, it is evident that further adjustments are required to attain the 75% accuracy target.

* Recommendations for Improvement:

  * Data Variety Matters: Expanding the dataset to include various types of applications and classifications may provide the model with a broader understanding of the problem.


