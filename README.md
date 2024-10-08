# The 24th International Conference on Artificial Intelligence,2022 the World Congress in Computer Science, Computer Engineering, & Applied Computing
# Springer Nature Transactions on Computational Science & Computational Intelligence(will be published) https://american-cse.org/csce2022/publisher
# Brain Tumor Classification on MRI in Light of Molecular Markers
Jun Liu1,2, Geng Yuan2, Wenbin Zhang3,Xue Lin2, XiaoLin Xu2, Yanzhi Wang2 

1Robotics Institute, School of Computer Science, Carnegie Mellon University, Pittsburgh, PA, USA

2 Department of Electrical & Computer Engineering, College of Engineering, Northeastern University, Boston, MA, USA

3 University of Maryland, Baltimore County, MD USA

Abstract. Codeletion of chromosomal arms 1p/19q has been connected to a good response to treatment in low-grade gliomas (LGG) in several studies. The ability to predict 1p19q status is critical for treatment planning and patient follow-up. The goal of this research is to develop a non-invasive approach based on MR images using our novel convolutional neural networks. Although public networks such as VggNet, GoogleNet and other well-known public networks can effectively diagnose brain cancers using transfer learning, but the model contains a huge number of components that are unrelated to medical image. As a result, the diagnostic results are unreliable by transfer learning model. In order to address the issue of trustworthiness, we build the model from the bottom up, rather than relying on transfer learning. Our network structure flexibly uses a deep convolution stack mixed with a dropout and dense operation, which reduced overfitting and enhanced performance. We also augmented the given dataset. The Gaussian noise is introduced during the model training. We use three--fold cross-validation to train the best selection model. Our proposed model is compared to MobileNetV2, InceptionResNetV2 and VGG16 that have been fine-tuned through transfer learning. Our model achieves better results than these models. When classifying images between 1p/19q codeletion and not codeleted, the proposed architecture achieved an F1-score of 96.37%, Precision 97.46%, Recall 96.34% in the test set.
Keywords. low-grade gliomas;  1p/19q;  CNN; reliability transfer learning;  radiogenomics.
