<h1>Deepfake Detection Project</h1>
<h2>Objective and Methodology</h2>
This project aims to tackle the growing concern around deepfake technology by developing a robust deepfake detection system. Deepfakes, synthetic media generated by Generative Adversarial Networks (GANs), pose significant risks in misinformation and privacy violations. We employed deep learning models to distinguish between real and artificially generated faces. Utilizing the 140k Real and Fake Faces dataset from Kaggle, which consists of 70k real faces from Flickr and 70k GAN-generated fake faces, we trained our models on 100k images, using 20k each for validation and testing.

Our methodology revolves around experimenting with DenseNet models and a custom Convolutional Neural Network (CNN) to identify the nuances between real and fake imagery effectively. By leveraging DenseNet's dense connectivity and our custom CNN's tailored architecture, we've aimed to maximize accuracy and efficiency in detection tasks.

<h2>Key Project Details</h2>
<h3>Execution Environment:</h3> Portions of this project were executed on a Windows machine equipped with an NVIDIA GPU, while other parts were run on a Mac. It is crucial to verify paths and settings according to your execution environment before running the project.
<h3>Dataset Requirement:</h3>h3> The project relies on Kaggle's 140k Real and Fake Faces dataset. Due to its size, we could not include it in the repository. Users need to download this dataset from Kaggle to replicate our results.
<h3>Repository Structure:</h3>h3>
Custom CNN Folder: Contains the code and model for our custom Convolutional Neural Network designed for deepfake detection.
DenseNet Models Folder: Hosts the models and code for the DenseNet121 experiments, including the base model, the model with image augmentations, and the model trained on grayscale images.
Performance_Demo Notebook: A Jupyter notebook that allows loading the trained models to classify uploaded images as real or fake.
ROC and PCA Notebooks: Includes notebooks for plotting the Receiver Operating Characteristic (ROC) curves and Principal Component Analysis (PCA) plots for all models, providing insights into model performance and feature distribution.
Running the Project
To successfully run and replicate our deepfake detection experiments, please follow these steps:

Environment Setup: Ensure your Python environment is configured correctly for either a Windows (with NVIDIA GPU) or Mac setup. Libraries and dependencies might require specific versions based on the operating system and hardware.
Dataset Download: Obtain the 140k Real and Fake Faces dataset from Kaggle and place it in the appropriate directory within the project. Update any paths in the code to reflect your dataset's location.
Explore the Repository: Familiarize yourself with the structure and contents of the repository, including the two main folders for the custom CNN and DenseNet models, and the Jupyter notebooks for demonstrations and analyses.
Performance Demonstration: Use the Performance_Demo notebook to load pre-trained models, upload images, and classify them as real or fake. This interactive tool is excellent for understanding the models' capabilities firsthand.
Analysis Notebooks: For deeper insights, the ROC and PCA plotting notebooks offer detailed visualizations of model performance and the feature spaces learned by the models.
By adhering to these guidelines, users can explore and extend our work on deepfake detection, leveraging the provided models and tools to test new data, refine the approaches, or develop new methodologies based on our foundational research.
