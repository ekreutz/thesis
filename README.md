# Thesis

I'm sharing my thesis titled "Active learning for annotation and recognition of faces in video." The thesis was given the overall grade 4 out of 5. The full grading assessment by my supervisor is also attached in this repo.

**Completed:** Feb 2021, Aalto University, Finland.

**Key words:** machine learning, artificial intelligence, deep learning, active learning, face detection, face recognition, face tracking, video,
film, movies

# Abstract

Data scarcity is often a concern when working with real-world datasets. From a machine learning point of view, it is problematic when datasets are not pre- labeled, so supervised learning cannot be easily performed.

In this thesis, a novel annotation pipeline for video data is introduced that aims to solve this problem. The system consists of a data extraction phase, as well as a labeling architecture and user interface. Various techniques and models from active learning, face detection, face recognition and object tracking are used and improved upon to put together an end-to-end system.

Importantly, the pipeline builds upon many recent advances within face detection and recognition, that utilize deep convolutional neural networks. The single-stage neural face detector used enables accurate trajectories of faces to be formed. Additionally, another neural model is used to create embedding vectors of faces, which are then used for clustering.

The system is evaluated in terms of labeling cost and noise, against a new dataset of Finnish feature films. It is determined that the labeling effort is reduced by orders of magnitude, as compared to a naive approach.
