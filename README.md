# Deep-Learning-Challenge
Introduction In the context of the Deep Learning Challenge, I have made several attempts to build a neural network model that accurately predicts outcomes based on the given dataset. The primary objective was to achieve an accuracy of 75% or higher in our predictions. This report will summarize our three attempts and discuss the results, including loss values, accuracy, and potential improvements for future attempts.

Attempt #1 In our first attempt, I have employed the following configuration:

APPLICATION_TYPE cutoff: 528 CLASSIFICATION cutoff: 1883 Layer 1: 80 neurons with a ReLU activation function Layer 2: 30 neurons with a ReLU activation function Results:

Loss: 0.5556 Accuracy: 72.87% Observations:

The loss value indicates that the model can be further optimized. The accuracy of 72.87% falls short of our target accuracy of 75%.

Attempt #2 In my second attempt, I made adjustments to the cutoff values while keeping the neural network architecture the same as in Attempt #1:

APPLICATION_TYPE cutoff: 66 CLASSIFICATION cutoff: 95 Results:

Loss: 0.5586 Accuracy: 73.27% Observations:

Despite the changes in cutoff values, the model's performance did not show significant improvement. The accuracy remains below the desired 75%.

Attempt #3 For our third attempt, I made modifications to the neural network architecture while retaining the initial cutoff values:

Layer 1: 88 neurons with a ReLU activation function Layer 2: 44 neurons with a tanh activation function Layer 3: 22 neurons with a ReLU activation function Results:

Loss: 0.5639 Accuracy: 72.88% Observations:

Once again, the model's performance did not reach the 75% accuracy threshold. The changes in the neural network architecture did not yield the desired improvement.

Conclusion and Recommendations In my first attempt reached an accuracy of 72.87%, and despite trying different cutoff values in the second attempt, I only improved slightly to 73.27%. In the third attempt, I have changed the model's structure but still didn't quite reach our target, achieving an accuracy of 72.88%. I've made progress, but it's clear that we need to make more adjustments to hit that 75% accuracy mark. Data Variety Matters: Adjustment like more data of diffrent type of Application and classification.
