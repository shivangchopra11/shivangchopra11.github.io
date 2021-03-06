---
title: "Face Recognition"
excerpt: "A light weight face recognition implementation using a pre-trained Facenet model.<br/><img src='/images/FaceRecognition.gif'>"
collection: portfolio
---

A light weight face recognition implementation using a pre-trained Facenet model. 

Faces in the frame are detected using HaarCascades and then classified using Facenet and Densenet.

First my training images are passed through the model and embeddings are created. Then a separate Densenet is trained to recognise the respective embeddings and predict the correct label.

A basic implementation using KNN is also included in the FaceRecogBasic folder.

# Demo
![Alt text](https://shivangchopra11.github.io/images/FaceRecognition.gif)

# References
Facenet Paper: [FaceNet: A Unified Embedding for Face Recognition and Clustering](https://arxiv.org/pdf/1503.03832.pdf)

Facenet Pre-trained Model: [Facenet Pre-Trained](https://github.com/davidsandberg/facenet)

