In this project, using a pre-trained network ResNet18 on a data set from the Kaggle website https://www.kaggle.com/datasets/tanliheng/hot-dog, the following was implemented:
1) Implemented my own Dataset class (HotdogOrNotDataset)
2) Implemented a neural network training circuit in the train_model function
3) Network errors were calculated in the _accuracy function
4) Implemented a function to display 10 random images and predicted model classes
5) In the RetrofittedResNet class, the last layer was rewritten and the model was additionally trained only on this layer
6) Next, I also changed the last layer to a new one, but in this case I retrained the entire model
7) I implemented different learning rates for all layers.
The last layer had a learning rate = 1e -3, and the rest of the model had a learning rate = 1e -4
8) At this point I visualized 10 random false positive images and
false negatives that the model did not predict correctly.
9) As the last point, I displayed the error metrics precession, recal and f1
