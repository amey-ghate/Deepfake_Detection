<h1>DeepInsight: Navigating the realm of Deepfake detection</h1> 
by Barnana Ganguly
Abhijit Anil
Amey Ghate
Rathil Madihalli
Sankalp Kulkarni
Shrishty Mishra


![Concerns GIF](Concerns.gif)

<h2>Objective and Methodology</h2>
This project aims to tackle the growing concern around deepfake technology by developing a robust deepfake detection system. Deepfakes, synthetic media generated by Generative Adversarial Networks (GANs), pose significant risks in misinformation and privacy violations. We employed deep learning models to distinguish between real and artificially generated faces. 

Utilizing the 140k Real and Fake Faces dataset from Kaggle, which consists of 70k real faces from Flickr and 70k GAN-generated fake faces, we trained our models on 100k images, using 20k each for validation and testing.

Our methodology revolves around experimenting with DenseNet models and a custom Convolutional Neural Network (CNN) to identify the nuances between real and fake imagery effectively. By leveraging DenseNet's dense connectivity and our custom CNN's tailored architecture, we've aimed to maximize accuracy and efficiency in detection tasks.

<h2>Key Project Details</h2>
<h3>1. Execution Environment:</h3> Portions of this project were executed on a Windows machine equipped with an NVIDIA GPU, while other parts were run on a Mac. It is crucial to verify paths and settings according to your execution environment before running the project.
<h3>2. Dataset Requirement:</h3> The project relies on Kaggle's 140k Real and Fake Faces dataset. Due to its size, we could not include it in the repository. Users need to download this dataset from Kaggle to replicate our results.
<h3>3. Repository Structure:</h3>
<h4>a. Custom CNN Folder:</h4> Contains the code and model for our custom Convolutional Neural Network designed for deepfake detection.
<h4>b. DenseNet Models Folder: Hosts the models and code for the DenseNet121 experiments, including the base model, the model with image augmentations, and the model trained on grayscale images.
<h4>c. Performance_Demo Notebook: A Jupyter notebook that allows loading the trained models to classify uploaded images as real or fake.
<h4>d. ROC and PCA Notebooks: Includes notebooks for plotting the Receiver Operating Characteristic (ROC) curves and Principal Component Analysis (PCA) plots for all models, providing insights into model performance and feature distribution.

<h3>4. Running the Project</h3>
To successfully run and replicate our deepfake detection experiments, please follow these steps:
<h4>a. Environment Setup:</h4>Ensure your Python environment is configured correctly for either a Windows (with NVIDIA GPU) or Mac setup. Libraries and dependencies might require specific versions based on the operating system and hardware.
<h4>b. Dataset Download:</h4> Obtain the 140k Real and Fake Faces dataset from Kaggle and place it in the appropriate directory within the project. Update any paths in the code to reflect your dataset's location.
<h4>c. Explore the Repository:</h4>Familiarize yourself with the structure and contents of the repository, including the two main folders for the custom CNN and DenseNet models, and the Jupyter notebooks for demonstrations and analyses.
<h4>d. Performance Demonstration:</h4> Use the Performance_Demo notebook to load pre-trained models, upload images, and classify them as real or fake. This interactive tool is excellent for understanding the models' capabilities firsthand.
<h4>e. Analysis Notebooks:</h4> For deeper insights, the ROC and PCA plotting notebooks offer detailed visualizations of model performance and the feature spaces learned by the models.
By adhering to these guidelines, users can explore and extend our work on deepfake detection, leveraging the provided models and tools to test new data, refine the approaches, or develop new methodologies based on our foundational research.

<h3>Note on Model Files:</h3> The .h5 files containing the trained models are too large for inclusion in this repository. However, by running the provided code in the respective environment setup (Windows with NVIDIA GPU or Mac), you can recreate these model files yourself. This ensures that you have the latest version of the models, directly tailored to your system's specifications and performance capabilities.
