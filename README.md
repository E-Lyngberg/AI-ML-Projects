# AI-ML-Projects
A repository to store links to relevant AI-ML projects that I have contributed to or written myself over the last few years. These are just a few projects that I have direct access to and no conflicts with posting publicly for reference, but is certainly not exhaustive of the types of architectures I have built and data I have analyzed. Most of these are stored in google colab notebooks that can be accessed via the links provided.


## Star Trek Neural Network

In a Computational Data Analytics course taken my sophomore year of undergraduate studies I was tasked with broad creative allowance to build a machine learning model to perform a task. My group member and I decided that it would be both fun and a great exploration of image preprocessing and analysis techniques to build a convolutional neural network to classify Star Trek ships based on their faction. This endeavour turned out to be more educational than anticipated, as we came to realize that the preprocessing of the images that we sourced from various Star Trek fan websites was more important than the complexity of the Neural Network itself. 

[Star Trek Neural Network and Image Edge Detection via Sobel Filter](https://colab.research.google.com/drive/1R6SccjWHyJ_9DNzcatDPD_WzPjBQJ25F?usp=sharing)

## Autoencoder for Encoding and Decoding 3D Objects and Anomaly Detection in Lung Scans

In a Mathematical Methods in Data Science course taken in my senior year of undergraduate studies, a fellow student and I built an autoencoder to learn more about the abilities of autoencoders to be used for encoding and decoding data with various latent layers. Depending on the depth of the autoencoder, one can retain as much as or as little latent information regarding the original dataset as needed. We have shown through this work that with a latent representation that is much smaller than the original data we can still retain most of the necessary information to reconstruct the original 3-D object and have it still be completely recognizable by a human. This type of latent information analysis will only become more and more important with future iterations of generative AI models, as the scaling required in deep understanding of natural language, images, etc. will require us to be able represent them with much less data than the original files in order to make computation more efficient.

Regarding the anomaly detection, we explored the use of autoencoders for detecting Pneumonia in lung chest X-ray scans as well as brain tumors via MRI scans of the brain. The idea is that a good autencoder should be able to reconstruct healthy brain and lung scans accurately because they almost all look alike, however whenever there is an anomalous tumor or pneumonia present in the brain and lungs respectively, then the autoencoder should struggle more to reconstruct the image effectively, and that will be reflected in reconstruction loss of that image. Through careful tuning and testing with a consistent data set of healthy scans, we can get a narrow band of reconstruction losses for typical scans and then for any future scan if it falls outside of that narrow band, we can be assured that there is something anomalous in that scan.

[Autoencoder Exploration on Simulated Data for 3 Dimensional Swiss Roll and S-Curve](https://colab.research.google.com/drive/1NWcY2Jhzax_7BAAGwZw_HBeM7jHc0Y_X?usp=sharing)

[Autoencoder Report on Dimensionality Reduction on Simulated Data and Anomaly Detection on Brain MRI Scans and Chest X-rays](https://github.com/E-Lyngberg/AI-ML-Projects/blob/main/Autoeconder_Paper.pdf)


