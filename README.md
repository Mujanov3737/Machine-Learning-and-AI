# Machine Learning
Artificial intelligence and the resulting applications emerging from the training of machine learning models are quite exciting. With ChatGPT being regarded as one of the fastest growing consumer applications ever, it is no wonder that AI will play a large role in the future of many facets of society, but particularly in the tech industry.
Contained within this repository are a 3 notebook scripts that utilize the Keras API and the TensorFlow platform to explore the applications and innerworkings of machine learning. a number of simple machine learning applications were studied, such as models that can identify hand-written digits, simulate balancing a pole on a track, and navigate a maze efficiently to find a particular objective while avoiding hazards. The latter model is what is contained within this repository. Also covered were the many ethical and societal implications AI content may bring with it.
### ML_1 Identifying Handwritten Digits with MNIST Handwritten Digits Database
The script contained in the first folder imports images from the categorized MNIST database containing handwritten digits and trains a convolutional neural network to identify the digits. The script is run 3 times and the number of Epochs used is raised and lowered for comparison. An Epoch is a term for one iteration or pass through the dataset while a model is being trained. Generally, for this model, it can be stated that increasing the number of Epochs increases accuracy but eventually provides diminishing return. There are some additional thoughts appended near the end of the script file.
### ML_2 Identifying Images with CIFAR-10 Image Database
The second script file utilizes the CIFAR_10 database of images in order to train a deep learning model to identify an image categorically. Each iteration of the script incorporates some changes, with first a base case, a case with a deeper network with more convolution operations, and finally a case with data augmentation to generate more images. In general, there are a number of strategies that can be leveraged and combined to boost the accuracy of a model, if used correctly. Appended at the end of this file are some thoughts on facial recognition technologies and ethical implications for how AI might be used in this manner.
### ML_3 Treasure Hunt Deep-Q Learning
The basic premise of the treasure hunt script is as follows: there is a player who must navigate a tile-based maze, avoid hazards, and ultimately reach a treasure chest to complete the game. Meanwhile, a non-playable antagonist in the form of a pirate is also attempting to reach the treasure before the player. This third folder contains a few python scripts and a Jupyter notebook that outlines the deep Q-learning algorithm and reinforcement learning principles used to train the pirate character to efficiently navigate the maze and defeat the player, with the help of the Keras library. A significant portion defining the structure of the game was pre-written, with the primary focus being to implement an accurage deep-q learning algorithm to train the pirate character effectively.
### AI in Computer Science
On a more general note, machine learning and AI is quite a complicated field where developers and other professionals must come up with models and algorithms so that tasks can be performed without the traditional types of programming of input => output. While some problems are well suited for traditional programming, others contain a high level of complexity that can only realistically be achieved using machine learning, such as identifying a human hand from various positions, races, and angles. Though that may be a trivial example, other more serious applications involve real world problems such as predicting the three-dimensional structure of a protein based on its amino acid profile, which OpenAI’s AlphaFold has made significant strides toward using deep learning techniques.
The significant challenge facing these types of organizations and developers is the plethora of ethical implications in AI products. These range from the privacy and security implications of data collection from users in order to train models to perform particular functions, to the transparency in how AI applications generate the data they generate, to even the potential impact AI may have in the future on jobs, businesses, or society at large.
