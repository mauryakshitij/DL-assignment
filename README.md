# CS590-Deep Learning-Probabilistic Generative Modelling
 
# Content
1. We have added the code for SOTA implementation of DDPM in the notebook- ddpm.ipynb
2. We have added the code for SOTA implementation of DDIM in the notebook- ddim.ipynb
3. We have added the code for our proposed hybrid approach using diffusion models+GAN
   a. Using ddpm + a pre-trained GAN on mnist
   b. We first trained our own GAN on mnist dataset and then used it after ddpm for generation.
4. You can find more details about our approach in the report and presentation slide deck.


# Datasets and Pre-trained Model Weights
- Dataset used for SOTA Implementation of DDPM in the notebook ddpm.ipynb -> mnist : https://www.kaggle.com/datasets/mauryakshitij/ddpm-mnist
- Dataset used for SOTA Implementation of DDIM in the notebook ddim.ipynb -> cifar10 : https://pytorch.org/vision/main/generated/torchvision.datasets.CIFAR10.html
- Pretrained GAN generator model weights: https://www.kaggle.com/models/mauryakshitij/mnist_gen
- Pretrained GAN discriminator model weights: https://www.kaggle.com/models/mauryakshitij/mnist_disc

# Instructions to run the code
Since we have uploaded all the work in notebooks, you can just upload the datasets, model weights, and update the paths accordingly in the notebook, and run the code with all the dependencies from requirements.txt installed on your system. You should run the code on a GPU since we process image data.
 
## Team Members
1. Achintya Gupta
2. Kannan Rustagi
3. Kshitij Maurya
4. Parth Kasture
5. Shashank Kumar

