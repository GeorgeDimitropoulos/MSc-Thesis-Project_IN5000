# MSc-Thesis-Project_IN5000
This repository contains my Master thesis project that I implemented in Python (in form of Jupyter notebooks) as a Data Science Research Intern at IBM Netherlands in collaboration with the Faculty of Electrical Engineering, Mathematics and Computer Science of TU Delft the period 2018-2019

As a Data Science Research Intern I was responsible to develop and implement a methodology that
increases fairness in Machine Learning image data.

More specifically, I developed an algorithm which detects, understands and mitigates bias with respect to
protected attributes of people in Machine Learning image data through semantic description
(human understanding level, interprete and explain predictions made by Machine Learning systems)
of the attention mechanism (identifies parts of an image that trigger a Machine (Deep) Learning model).

The research hypothesis which I verified was that presence of specific visual clues in images,
that give away the protected attribute of people (gender in my case), affects the classification
outcome and introduces bias on that. The use-case that I explored was the gender bias in
profession prediction from images (easily applicable to other Machine (Deep) Learning applications).

Main tasks:

■Bias detection for the problem of classification for Machine Learning image data through statistical analysis
 and experimentation.

■Bias semantic interpretation (find parts of the image that affect the classification outcome) through combining
 an attention mechanism, object detection and crowdsourcing to gain an insight of how the intuition of people
 about elements of gender bias matches the semantic description coming from object detection.

■Bias mitigation through implementing image processing transformations

Algorithms used: Neural Networks for Classification, SmoothGrad for Attention mechanism,
YOLO for Object Detection, Connected Component Analysis and Interesection over Union metric
for Image processing and correlation between Attention mechanism, Object Detection and Crowdsourcing.

Technologies used : The whole implementation was in Python with the usage of the packages:

■Numpy
■Pandas
■Scikit Learn
■Keras
■Pytorch
■SciPy
■Matplotlib
■Seaborn
■OpenCV
■Scikit-image
■PIL and Pillow

The Crowdsourcing task was done in Figure-Eight
