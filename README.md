# PhD Thesis 
A dissertation submitted to the University of Leicester in accordance with the requirements of the degree of DOCTOR OF PHILOSOPHY in the Faculty of Informatics.
JULY 2020

## Engineering Lossless Sequence Prediction with Compact Data Structures

Sequences of symbols can be used to represent data in many domains such as text documents, activity logs, customer transactions and website click- streams. Sequence prediction is a popular task, which consists of predicting the next symbol from a sequence of symbols, given a set of training sequences (under identical symbol set). Although numerous prediction models have been proposed, many have a low accuracy because they are lossy models (they discard information from training sequences to build the model), while lossless models are often more accurate but typically consume a large amount of memory. This thesis addresses the challenges of lossless sequence prediction approaches by engineering an existing state-of-the-art lossless sequence prediction algorithm through space efficient data structures. Moreover, during this thesis, we propose a novel and lossless sequence prediction model that overcomes most of the challenges that usually make a lossless approach suffer. We utilise succinct data structures to compactly represent and efficiently access training sequences for prediction. Based on our experimental evaluations, our lossless SCPT and SUBSEQ prediction algorithms, achieve a very low and consistent memory consumption while maintaining a competitive execution performance. Moreover, with SUBSEQ, we demonstrate an excellent accuracy when compared to eight state-of-the-art prediction algorithms on seven real-life datasets. Finally, we further examine the significance of lossless approaches in the sequence prediction domain, and we present a new ensemble approach that blends lossy and lossless sequence prediction models for a much more improved accuracy performance.

[Direct link to the Thesis material through the e-library of University of Leicester](https://le.ac.uk/library)
