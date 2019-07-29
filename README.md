# machineLearningMaterials
Collection of machine learning related things

### Tutorials, ideas
- [A Recipe for Training Neural Networks](http://karpathy.github.io/2019/04/25/recipe/) by Andrej Karpathy
- initial bias settings for unbalanced sets: https://stackoverflow.com/questions/40708169/how-to-initialize-biases-in-a-keras-model

### Architectures
- [Wavenet](https://deepmind.com/blog/wavenet-generative-model-raw-audio/) : instead of recurrent /LSTM net use diluted convolution
  - Oord, A.V.D., Dieleman, S., Zen, H., Simonyan, K., Vinyals, O., Graves, A., Kalchbrenner, N., Senior, A. and Kavukcuoglu, K., 2016. Wavenet: A generative model for raw audio. arXiv preprint arXiv:1609.03499. [link](https://arxiv.org/pdf/1609.03499.pdf)
  - [recurrent vs. convolutional blog @ Berkeley](https://bair.berkeley.edu/blog/2018/08/06/recurrent/)
  - Bai, S., Kolter, J.Z. and Koltun, V., 2018. An empirical evaluation of generic convolutional and recurrent networks for sequence modeling. arXiv preprint arXiv:1803.01271. [link](https://arxiv.org/abs/1803.01271)
- [UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction](https://umap-learn.readthedocs.io/en/latest/) : faster and maybe better than t-SNE
  - https://arxiv.org/pdf/1802.03426.pdf
  - also the paper has an interesting dimension reduced representation of whole numbers from prime factor representation (Fig. 9-11)
- __Warped convolutions__ Henriques, J.F. and Vedaldi, A., 2017, August. Warped convolutions: Efficient invariance to spatial transformations. In Proceedings of the 34th International Conference on Machine Learning-Volume 70 (pp. 1461-1469). JMLR. org. [link](https://arxiv.org/abs/1609.04382) 
  - this may be good for nanopore data analysis, where the speed of DNA reading may vary  
