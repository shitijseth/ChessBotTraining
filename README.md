# ChessBotTraining
Training a Neural Network on my chess games

Note- This project is ongoing and consistent modifications and improvements will occur.

Here’s a brief summary of the key results:

Accuracy Improvement:
The training accuracy increased from roughly 3.6% in Epoch 1 to around 14–15% by Epoch 25, with the validation accuracy following a similar trend.

Loss Reduction:
The loss value dropped from over 16 initially to about 5.2 toward the later epochs, indicating that the network’s predictions are becoming more confident.

Context of Performance:
Although a 14–15% accuracy might appear low, it is significantly higher than the 0.024% (1/4096) chance level for random guessing. This means your model is learning meaningful patterns from your game data.

Tuning Directions:
Based on these results, further improvements are anticipated by:

Adjusting dropout rates and adding batch normalization for more stable training.
Incorporating learning rate scheduling and early stopping to refine convergence.
Exploring alternative architectures (such as convolutional networks that preserve spatial structure) to better capture the nuances of chess positions.
