# SCO-dataset
Machine learning datasets can be used for network training and testing of various intelligent tasks involving deep learning and intelligent tasks. There is also a class of datasets for human ratings, which can support users' evaluation of the quality, preferences, etc. of video or picture data. However, neither of these two datasets considers the fusion of communication and computation, and can not support the study of semantic communication. Therefore, we propose the SCO dataset, a dataset for semantic communication. It contains 100 original images (from Pascal dataset) and 5000 distorted images. We add 3 types of distortion (JPEG compression, Gaussian blur, Gaussian noise) to each image, each type of distortion has 10 levels, and in order to simulate the actual communication process, we combine the above 3 types of distortion to generate the fourth type of superposition distortion, There are a total of 20 levels of superimposed distortion, and a total of 5000 distorted images. All distorted pictures were scored by 30 volunteers, and the greater the degree of distortion, the lower the score.

The proposed dataset can support the following studies: constructing resource allocation objective functions for semantic communication; training siamese neural networks for semantic distortion evaluation; comparing the difference between human experience and machine understanding, etc. With the development of semantic communication, we believe this dataset will spark more research topics in the future. It is worth mentioning that using the constructed distortion data set for the training of the deep learning model can verify the robustness of the deep learning model in the presence of communication interference.

We have made the dataset publicly available，you can download it here.https://drive.google.com/drive/folders/1UxJtMtVO_1OfBiCf30zz3Ki13KVBsUd9?usp=sharing
