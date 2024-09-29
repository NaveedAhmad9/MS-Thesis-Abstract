# MS-Thesis-Abstract
Due to the increasing number of skin diseases, it has become an active research topic for
 medical imaging. There are a lot of types of skin cancer and melanoma is one of them. Melanoma is
 caused mainly by UltraViolet (UV) radiation and is the most harmful type of cancer that must be
 diagnosed early. To solve these types of skin cancer, a new methodology is proposed in this work.
 Hence, we use two publicly available datasets including HAM10000 and ISIC 2018. In these datasets,
 data augmentation is applied to increase the training data. Transfer learning is used to train fine
tuned pre-trained models including Xception and ShuffleNet. The global average polling layer is
 utilized to extract features from both deep models to obtain two feature vectors and then the
 Serial-Threshold fusion approach is used to fuse those features. Afterward, we apply the Butterfly
 Optimization Algorithm (BOA) feature selection method on the fused feature vector to obtain the
 optimal feature vector. Finally, the selected optimal feature vector is classified through numerous
 Machine Learning (ML) classifiers including SVM and Neural Network (NN). The resulting accuracy
 for both datasets is 99.3% and 91.5% respectively. Comparison of accuracy showed that the
 proposed technique increases computing efficiency and classification accuracy.
