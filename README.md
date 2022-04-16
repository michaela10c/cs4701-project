# Neural Networks: When are they Useful? An Analysis of Three Different Datasets

Authors: Michael Zhou (mgz27), Qiaochu Xiong (qx27), Brian Ling (bjl95)


This project illuminates the different types of situations when neural networks are met, as
analyzed on different datasets. We built a suite of neural networks - different implementations of
fully-connected neural networks (FCNNs) and convolutional neural networks (CNNs). 

We tested some of these architectures on the following datasets: 
- Musical Notes Datasets
- Email Spam Classification Dataset
- UCI Wine Quality Dataset. 

We analyzed both the test accuracies and runtimes of each model for each dataset. Our results corroborate that convolutional neural networks (CNNs) work well for image-based datasets (problems including image classification), at the cost of a longer training time due to the complex nature of its architecture. The size of the dataset also contributes to the training time, as a larger dataset implies a longer training time because of a larger input space. Moreover, FCNNs outperform CNNs on datasets that are densely populated by zero. We also noticed that weak correlations between predictors and unbalanced class distributions within the dataset yields a low test accuracy.

Final Project for Cornell course CS 4701 - Practicum in Artificial Intelligence 

Video Presentation: https://www.youtube.com/watch?v=rg1PmR6-gYc 

Slides: [CS 4701 Project Slides.pdf](https://github.com/michaela10c/cs4701-project/files/8499175/CS.4701.Project.Slides.pdf)

Final Report: [CS 4701 Final Report.pdf](https://github.com/michaela10c/cs4701-project/files/8499174/CS.4701.Final.Report.pdf)
