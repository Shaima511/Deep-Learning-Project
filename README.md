# Deep-Learning-Project
<b>Student Name:</b> Shaima Al Balushi

<b>Overview:</b> Using the CIFAR-10 dataset, this project attempts to investigate and use deep learning models for image categorization. The CIFAR-10 dataset is a perfect baseline for evaluating different convolutional neural network (CNN) designs since it contains 60,000 32x32 color pictures in 10 distinct classifications.

<b>Data Exploration and Preprocessing:</b> The project's initial steps include examining the CIFAR-10 dataset, putting representative images from each class into a visual representation, and getting the data ready for testing, validation, and training.

<b>Model Development and Training:</b> Two distinct methods are used to execute the modeling process:
<ul><li>Custom CNN:  The PyTorch Lightning  and PyTorch are used to create and train a custom convolutional neural network using the CIFAR-10 dataset.</li>
<li>Pre-trained ResNet and Transfer Learning: In order to take advantage of transfer learning, a pre-trained ResNet-18 model is refined using the CIFAR-10 dataset.</li></ul>

<b>Evaluation and Comparison:</b> The test dataset is used to assess the trained models' accuracy in putting photos into categories that are appropriate. Understanding the variations in performance between the customized CNN and the refined ResNet-18 model is possible through comparison.

<b>Structure of the Repository:</b>  <ul>
<li>Preprocessing Data: This section includes preprocessing, load of the data, and exploring scripts.</li>
<li>Models: Contain files of Python  that provide the pre-trained ResNet-18 structure and the tailored CNN.</li>
<li>Training and Evaluation: Consists of distinct modules for both model training and assessment.</li>
<li>Visualizations: Code for displaying model performance metrics and example photos is included here.</li></ul>

<b>How to Run:<ul><li></b>Refer to the directions in the corresponding README files inside each folder/module for information on how to launch the project.

<b>Additional Notes:</b>This work is an experiment in applying standard architectures and frameworks to deep learning models for picture categorization problems.</li>
<li>how to run it: Use the file DeepLEarning.ipynb
</ul>

<b>data source, and how you downloaded it:</b> The project's picture collection, known as CIFAR-10, has 60,000 32x32 color photos from ten distinct classes. Machine learning models are frequently trained and tested using these photos. We used the torchvision Python module to retrieve the CIFAR-10 dataset. During program execution, our code downloads the dataset dynamically from the official torchvision source if it isn't already in the designated location. With the use of picture analysis and this dataset, our computer software is able to pick up and identify a wide range of items, including vehicles, planes, birds, cats, and more.
