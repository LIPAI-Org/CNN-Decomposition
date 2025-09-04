# Oral Cavity Dysplasia Classification using Tucker Decomposition and CNNs

Oral cavity cancer is one of the most common types of cancer, making early diagnosis essential for investigating lesions with potential to develop into the disease. Dysplasias are early-stage lesions that may progress to more severe stages and are characterized by changes in the shape and size of epithelial cell nuclei.

Manual classification of histological images is time-consuming and highly dependent on the specialist’s experience. In recent years, Computer-Aided Diagnosis (CAD) systems have become valuable tools for classifying these images, thanks to advances in image processing and artificial intelligence. However, techniques used in CAD systems, such as Convolutional Neural Networks (CNNs), often suffer from over-parameterization.

This work investigates the use of Tucker decomposition on the kernels of convolutional layers in ResNet architectures to reduce the number of parameters. In addition to evaluating classification performance using the networks, feature maps from intermediate layers were analyzed using machine learning algorithms.

Key Results
- Tucker decomposition significantly reduces the number of parameters.
- Maintains high classification accuracy, especially on balanced histological image datasets.
- Feature maps from intermediate layers provide additional insights for machine learning–based classification.
