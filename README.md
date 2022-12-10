# idl-project
### Project description 

Birth asphyxia is a neonatal condition that is not only hard to identify, but is also the leading cause of neonatal deaths. Identifying neonates, or babies, with birth asphyxia would thus save numerous lives. Current models able to be put into practice use convolutional neural networks to identify neonates with asphyxia using Mel Frequency Cep Coefficients (MFCCs).  In this project, we outline several methods that achieved competent results that performed the same as our implementation of a baseline. In particular, we show that the performances of Linear Networks, Bi-directional LSTMs, and ResNet18 have similar Unweighted Average Recall (UAR) scores. However, upon bootstrapping and applying Tanh() distortion and Room Reverberation, UAR increases from the baseline UAR of 0.6 to 0.7. We thus propose that researchers in the field of Pathological Cry Analysis should focus less on model sophistication and more on bootstrapping techniques to increase data samples or generative models and tasks that can rely on fewer data samples to make high-accuracy results.


### Code Directions
Each Colab File represents a different aspect of our project. To run each collab file, simply run the cells sequentially. Issues that make be included involve improperly set filepaths. For these issues, please reset the filepath to the local directory where the Baby Chillanto Dataset is available
