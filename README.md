# DeepLearning-Courses-by-UW
华盛顿大学2017秋季学期深度学习课程 `T81 558:Applications of Deep Neural Networks` 

教授: [Jeff Heaton](https://sites.wustl.edu/jeffheaton/)

2017秋季学期，每周一

**需注意, 用的版本为 TensorFlow 1.0.**

# 课程说明

Thanks to Professor [Jeff Heaton](https://sites.wustl.edu/jeffheaton/).I really love your courses.
非常感谢华盛顿大学教授 `Jeff Heaton` 的课程，github 里面没有讲义，可以去[华盛顿大学课程](https://sites.wustl.edu/jeffheaton/t81-558)网站找找，我没找到，另外可以看看教授的博客 [Blog of Jeff Heaton](http://www.heatonresearch.com/jeff/),感觉比较接地气，不是那种只会说不会实践的老师。博客里面有一些有用的东西，例如一些传到 `YouTube` 的视频，当然不翻墙肯定看不了。另外，本课程跑代码的环境是 `Anaconda` 或者 `jupyter notebook`。最后，下面是原课程介绍，只是翻译了一下。

深度学习是令人兴奋的神经网络新技术。通过使用先进的训练技术和神经网络架构组件，现在可以训练复杂得多的神经网络。本课程将向学生介绍深度神经网络，正则化单元（`ReLU`），卷积神经网络和（`CNN`）递归神经网络(`RNN`)。高性能计算（`HPC`）方面将展示如何在图形处理单元（`GPU`）上利用深度学习。深度学习使模型能够以与人类大脑功能类似的方式来学习信息的层次结构。重点将主要放在深度学习的应用上，并介绍深度学习的数学基础。学生们将使用Python编程语言,TensorFlow和Keras来构建一个真实数据集的深度学习模型，并解释这些网络的结果。

# 目标
1. 比较深度神经网络和其他机器学习模型的比较。
2. 确定在何时对于特定问题，深度神经网络是好的选择。
3. 通过最终项目，展示你对课程的理解程度。

# 课程安排

Class|Content
---|---
[Class 1](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class1_intro_python.ipynb)<br>08/28/2017 | <ul><li>Python for Machine Learning</ul>
LABOR DAY<br>09/04/2017 | ** No class labor day **
[Class 2](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class2_tensor_flow.ipynb)<br>09/11/2017 | <ul><li>Neural Network & Machine Learning Basics<li>Introduction to TensorFlow<li>Assignment: Read Chapter 1</ul>
[Class 3](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class3_training.ipynb)<br>09/18/2017 | <ul><li>Training a Neural Network<li>Assignment: Read Chapters 4 & 5</ul>
[Class 4](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class4_class_reg.ipynb)<br>09/25/2017 | <ul><li>Classification & Regression</ul>
[Class 5](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class5_backpropagation.ipynb)<br>10/02/2017 | <ul><li>Backpropagation<li>Assignment: Read Chapter 6, <b>Program 1 Due (Tuesday, 10-03 at midnight)</b></ul>
[Class 6](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class6_preprocessing.ipynb)<br>10/09/2017 | <ul><li>Preprocessing<li>Assignment: <b>Program 2 Due (Tuesday, 10-10 at midnight)</b></ul>
Fall Break<br>10/16/2017 | **No class session**
[Class 7](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class7_kaggle.ipynb)<br>10/23/2017 | <ul><li>Kaggle Datasets<li>Evaluating Neural Network Performance</ul>
[Class 8](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class8_cnn.ipynb)<br>10/30/2017 | <ul><li>Convolutional Neural Networks<li>Assignment: <b>Take Home Midterm Due (Tuesday, 10-31 at midnight)</b></ul>
[Class 9](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class9_regularization.ipynb)<br>11/06/2017 | <ul><li>Regularization and Dropout<li>Assignment: Read Chapter 12</ul>
[Class 10](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class10_lstm.ipynb)<br>11/13/2017 | <ul><li>Timeseries and Recurrent Neural Networks<li>Assignment: Read Chapter 13</ul>
[Class 11](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class11_nlp.ipynb)<br>11/20/2017 | <ul><li>Natural Language Processing<li>Assignment: Read Chapter 14, <b>Program 3 Due (Tuesday, 11-21 at midnight)</b> (submitted on Kaggle.com)</b></ul>
[Class 12](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class12_app.ipynb)<br>11/27/2017 | <ul><li>Applications of Neural Networks </ul>
[Class 13](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class13_other.ipynb)<br>12/04/2017 | <ul><li>Advanced Deep Learning Topics<li>Assignment: <b>Program 4 Due (Tuesday, 12-05 at midnight)</b></ul>
[Class 14](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/t81_558_class14_aws.ipynb)<br>12/11/2017 | <ul><li>GPU, HPC and Cloud<li>Assignment: <b>Final Project Due (Tuesday, 12-18 at midnight)</b></ul>

# 数据集

* [Iris](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/datasets_iris.ipynb) - Classify between 3 iris species.
* [Auto MPG](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/datasets_mpg.ipynb) - Regression to determine MPG.
* [WC Breast Cancer](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/datasets_wcbc.ipynb) - Binary classification: malignant or benign.
* [toy1](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/datasets_toy1.ipynb) - The toy1 dataset, regression for weights of geometric solids.

*Note: Other datasets will be added as the class progresses.

# 项目作业

* [Programming Assignment #1](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_项目作业1.pdf)
* [Programming Assignment #2](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_项目作业2.pdf)
* [Midterm](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_期中作业.pdf)
* [Programming Assignment #3](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_项目作业3.pdf) 
* [Programming Assignment #4](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_项目作业4.pdf)
* [Final Assignment](https://github.com/youngxiao/DeepLearning-Courses-by-UW/tree/master/pdf/UW_DP_期末作业.pdf)

# 其他

* [Helpful Functions](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/jeffs_helpful.ipynb) - 对课程有用的 Python 函数.
* [KDD99 Example](https://github.com/youngxiao/DeepLearning-Courses-by-UW/blob/master/tf_kdd99.ipynb)
* [Video Tutorial on Using Data Scientist Workbench](https://www.youtube.com/watch?v=9r6ZfZm9nmI) - YouTube 的教程，如何导入数据到 Data Scientist Workbench.
* [Care and Feeding of Python](http://www.heatonresearch.com/content/python_care.html) - 一些安装 package 有用命令。 如果您正在使用 Data Scientist Workbench，则不需要。
