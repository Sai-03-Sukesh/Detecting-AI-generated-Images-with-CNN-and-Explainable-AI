# Detecting-AI-generated-Images-with-CNN-and-Explainable-AI
This project focuses on developing a deep learning model to distinguish between real and AI-generated images using the DenseNet121 architecture. By leveraging a dataset of 140,000 images from Kaggle, the model achieves a high accuracy of 93.4% in classification tasks.Additionally, the integration of Gradient-weighted Class Activation Mapping (Grad-CAM) enhances the interpretability of the model, providing insights into its decision-making process. This project aims to contribute significantly to the field of image authentication and paves the way for future advancements in detecting synthetic media.

**Features**
1. **DenseNet121 Architecture**: Utilizes a pre-trained DenseNet121 model, customized for binary classification of real and fake images.
2. **High Accuracy**: Achieves a testing accuracy of 93.4% and an AUC score of 99.87%.
3. **Grad-CAM Visualization**: Implements Grad-CAM heatmaps to visualize and understand the regions influencing model decisions.
4. **Robust Dataset**: Employs a dataset of 140,000 images (70,000 real and 70,000 fake) from Kaggle, with real images sourced from Nvidia's Flickr collection and fake images generated using StyleGAN.
5. **Data Augmentation**: Applies various augmentation techniques to enhance model training and generalization.
