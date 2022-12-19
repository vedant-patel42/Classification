# Project Info
The project focuses on the MNIST data set to classify the multi class problem to improve the
performance on standardized methods by using an active-passive loss function. It contains
70,000 data samples i.e 60,000 training images and 10,000 testing images, each containing a
28x28 grid describing grayscale image values.

The goal for this implementation was to create a total of six models:
1. Classical SVM
2. Symmetric Cross Entropy Learning (SL)
3. A proposed ML implementation
4. A proposed DL implementation

And to compare and evaluate the performance of each against six versions of the
MNIST dataset:
1. Imbalanced (Original MNIST)
2. Balanced (Using SMOTE in the case of this implementation)
3. Imbalanced dataset with symmetric noisy labels
4. Imbalanced dataset with asymmetric noisy labels
5. Balanced dataset with symmetric noisy labels
6. Balanced dataset with asymmetric noisy labels
Using metrics like accuracy, precision, loss and confusion matrices.
