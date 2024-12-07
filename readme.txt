Batch B2
A Novel Deep Learning Approach for Classification of Eye Diseases using Fundus Images

Procedure:
1)Input Processing
Fundus RGB images are taken as input and converted into feature maps through the
application of a convolution layer. This initial step transforms raw image data into a format suitable
for deep learning models, enabling the identification of patterns and features indicative of various
eye diseases.
2)Model Training and Evaluation
Different deep learning architectures, including VGG16, ResNet, and DenseNet, are used to
train and evaluate the classification models. These architectures, known for their effectiveness in
image recognition tasks, are trained on a preprocessed Kaggle dataset. Data augmentation
techniques, such as horizontal flipping, are applied to enhance the models' robustness and
generalizability.
3)Performance Assessment
The performance of each architecture is assessed based on metrics such as accuracy,
precision, and recall. DenseNet achieves the highest accuracy of 96.68%, making it the most
effective model for classifying eye diseases from fundus images.
4)GUI Development
A user-friendly graphical user interface (GUI) is developed to facilitate practical application
and user interaction. This GUI allows for easy uploading of fundus images and provides immediate
classification results, enhancing the accessibility and usability of the deep learning model in realworld clinical settings.

Hardware & Software Requirements
Software Requirements: Platform - Google Colab, VS Code, Programming language – Python, HTML, JS.
Hardware Requirements: Intel core i7 with GPU(Graphics Processor Unit), 8GB and above hard disk capacity, 12GB RAM
