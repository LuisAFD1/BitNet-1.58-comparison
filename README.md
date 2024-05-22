# BitNet-1.58-comparison
Analysis of Loss and Accuracy FP8 and BitNet 1.58


Analysis of Loss and Accuracy
Training Loss:

FP8:
Starts with a loss of 0.2650 in the first epoch.
The loss fluctuates between 0.2650 and 0.3839 across the epochs.
The loss seems to increase and then stabilize around 0.34-0.38 in the later epochs.
BitNet 1.58:
Starts with a loss of 0.3066 in the first epoch.
The loss fluctuates between 0.2853 and 0.3920 across the epochs.
The loss also tends to fluctuate and stabilizes around 0.33-0.37 in the later epochs.
Training Accuracy:

FP8:
Starts with an accuracy of 95.78% in the first epoch.
The accuracy fluctuates between 94.74% and 95.83% across the epochs.
Generally maintains an accuracy around 95.30%.
BitNet 1.58:
Starts with an accuracy of 95.65% in the first epoch.
The accuracy fluctuates between 94.89% and 95.61% across the epochs.
Generally maintains an accuracy around 95.30%.
Conclusions
FP8:

Loss: Reaches a lower loss more quickly (in the first epoch) and maintains a more stable loss.
Accuracy: Has a high accuracy from the first epoch and maintains this accuracy throughout the epochs, with a slight increase in the sixth epoch (95.83%).
BitNet 1.58:

Loss: Starts with a higher loss compared to FP8 and has more fluctuations.
Accuracy: Also starts with a high accuracy but fluctuates more and does not show a clear pattern of consistent improvement.
Recommendation
Since both models achieve comparable accuracies at the end of the training, the FP8 model is preferable when considering faster convergence and stability of the loss. FP8 shows a lower loss from the first epoch and a stable accuracy in the early epochs, suggesting it needs fewer epochs to train effectively.

If you are looking for faster and more stable convergence, FP8 seems to be the better choice. However, for a more precise analysis, you might consider monitoring validation loss and accuracy during training.
