# idl-project
### Project description 

Birth asphyxia is a neonatal condition that is not only hard to identify, but is also the leading cause of neonatal deaths. Identifying neonates, or babies, with birth asphyxia would thus save numerous lives. Current models able to be put into practice use convolutional neural networks to identify neonates with asphyxia using Mel Frequency Cep Coefficients (MFCCs).  In this project, we outline several methods that achieved competent results that performed the same as our implementation of a baseline. In particular, we show that the performances of Linear Networks, Bi-directional LSTMs, and ResNet18 have similar Unweighted Average Recall (UAR) scores. However, upon bootstrapping and applying Tanh() distortion and Room Reverberation, UAR increases from the baseline UAR of 0.6 to 0.7. We thus propose that researchers in the field of Pathological Cry Analysis should focus less on model sophistication and more on bootstrapping techniques to increase data samples or generative models and tasks that can rely on fewer data samples to make high-accuracy results.


### Code Directions
Each Colab File represents a different aspect of our project. To run each collab file, simply run the cells sequentially. Issues that make be included involve improperly set filepaths. For these issues, please reset the filepath to the local directory where the Baby Chillanto Dataset is available

### Acknowledgement

In this project, we use The Baby Chillanto Data Base. 

The Baby Chillanto Data Base is a property of the Instituto Nacional de Astrofisica Optica y Electronica – CONACYT, Mexico.

We like to thank Dr. Carlos A. Reyes-Garcia, Dr. Emilio Arch-Tirado and his INR-Mexico group, and Dr. Edgar M. Garcia-Tamayo for their dedication of the collection of the Infant Cry database.
c. And a citation to the article “Orion Fausto Reyes-Galaviz, Sergio Daniel Cano-Ortiz, Carlos Alberto Reyes-García. "Evolutionary-Neural System to Classify Infant Cry Units for Pathologies Identification in Recently Born Babies". Proceedings of the Special Session MICAI 2008, Pg. 330- 335. Eds. Alexander Gelbukh & Eduardo Morales. IEEE Computer
Society. ISBN: 978-0-7695-3441-1.
