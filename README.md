# metagenomic-dimensionality-reduction
#### Reducing dimensions of higher dimensional metagenomic sequence data for visualizations using autoencoders.

[![](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/maduranga95/metagenomic-dimesionality-resuction/blob/master/LICENSE)

Autoencoders can be considered as a special type of neural networks, which consists of two symmetric components namely encoder and decoder. Encoder maps input to more compressed lower dimensions, in contrast to the decoder which does exactly the opposite. Autoencoders are an unsupervised learning technique that leverages reducing the dimensionality of the input vectors efficiently, such that it will preserve the important characteristics of the original data and then reconstructing the original data with minimum loss using compressed representation.

When the autoencoder is trained to sufficiently minimize the loss it can be used for dimensionality reduction. The high dimensionality data that is input to the autoencoder can be intercepted in the bottleneck layer before it reaches the decoder. The bottleneck layer gives a lower dimensional representation of the high dimensional input. 

Oligonucleotide frequencies can be represented as vectors in high dimensional Euclidean space. In the visualization of metagenomic data, without prior taxonomic references using sequence fragments, frequency vectors can be used as a genomic signature. We use autoencoders to reduce the high dimensionality of oligonucleotide frequency vectors and to obtain a visualizable dense representation.


### Setting up 
- Make sure you have Windows and Python 3.6.x environment
- Install Vectorizer 3.0 using wheel file ```vectorizer-3.0-cp36-cp36m-win_amd64.whl``` inside ```cpp_python_wheels``` folder.
- Install required python packages.

License
----

MIT
