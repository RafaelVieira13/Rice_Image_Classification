# Introduction

The primary objective of this project is to develop a robust and efficient image recognition system that can accurately classify different types of rice in images. To achieve this, we utilize the Rice Image Dataset, sourced from Kaggle. This dataset comprises a diverse collection of images featuring various types of rice grains, such as Arboriio, Basmati, Ipsala, Jasmine and Karacadag. The dataset serves as the foundation for training our model to learn the distinctive features and characteristics associated with each rice type.

To facilitate the deployment of our image recognizer model, we utilize the Hugging Face platform. Hugging Face provides an extensive suite of tools and infrastructure for hosting and sharing machine learning models, ensuring easy integration and accessibility. By deploying our model on Hugging Face, users can effortlessly upload rice images and obtain real-time predictions and classifications.

By combining the capabilities of Fast.ai and Hugging Face, this project offers a comprehensive solution for rice image recognition. Fast.ai provides an intuitive interface for training and fine-tuning deep learning models, while Hugging Face simplifies the deployment process, making the model readily available for use by individuals or applications.

The development of this image recognition system aims to showcase the potential of deep learning techniques in the field of rice grain classification. By accurately identifying different rice types from images, this technology can aid in quality control, inventory management, and grading processes within the rice industry.

Throughout this project, we will delve into the training process, model architecture, and optimization techniques employed to enhance the accuracy and performance of the image recognition system. Additionally, we will evaluate the model's performance against various evaluation metrics to assess its effectiveness in real-world scenarios.

In conclusion, this project utilizes Fast.ai and Hugging Face to develop an accurate and efficient image recognition system focused on rice grain classification. Leveraging the Rice Image Dataset, we train our model to identify different rice types from images. The outcomes of this project contribute to the advancement of computer vision in the rice industry, offering valuable insights and applications for automated rice grain classification and analysis.

# The DataSet

The Rice Image Dataset used in this project is sourced from Kaggle, a popular platform for machine learning datasets and competitions. This dataset provides a valuable resource for training and evaluating our rice image recognition model.

The dataset consists of a diverse collection of rice images, capturing various types of rice grains commonly found in the market. It includes images of different rice varieties such as Arboriio, Basmati, Ipsala, Jasmine and Karacadag. These images are carefully labeled and categorized according to their respective rice types, enabling supervised training of our image recognition model.

# The Model

The image recognition model developed in this project utilizes the Fast.ai deep learning library, which offers powerful tools and functionalities for training and fine-tuning convolutional neural networks (CNNs). This model is designed to accurately classify different types of rice grains based on their visual characteristics.

The architecture of the model follows a typical CNN structure, consisting of multiple layers that extract and process features from input images.

The model achieved a great performance as we can see by the following confusion matrix.

![image](https://github.com/RafaelVieira13/Rice_Image_Classification/assets/129581165/ecc858c1-1bfd-44ac-9bcd-6e2d65dea92c)

# Turining the Model into a APP

The deployment of the image recognition model in this project is facilitated through the Hugging Face platform. Hugging Face offers a comprehensive suite of tools and infrastructure for hosting, sharing, and deploying machine learning models, making it an ideal choice for deploying our rice image recognition system.

In the following link you can take a look at the model: 
https://huggingface.co/spaces/rafaelV13/Rice_Type_Classifier



