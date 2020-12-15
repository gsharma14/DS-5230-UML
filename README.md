# DS-5230 
## Unsupervised Machine Learning and Data Mining
### Being the next Monet! – Training Generative Adversarial Networks for Unpaired Style Transfer 
**Authors:** Gopalika Sharma and Surya Menon 

#### Abstract:
This project was focused on generating images to replicate the unique artistic style of Claude Monet, one of the founders of French Impressionism. Specifically, given a series of Monet paintings on which to train, our objective was to conduct unpaired image-to-image translation on a set of real-world photographs, resulting in the final images ultimately looking more like Impressionist paintings. To achieve this task, we implemented deep unsupervised learning methods in order to automatically discover the patterns in one domain so these stylistic details can be applied and reproduced in other examples. We explored a variety of generative adversarial networks, or GANs, to effectively achieve this style transfer, including deep convolutional GANs (DCGANs), fast neural style transfer, contrastive unpaired translation (CUT), and different versions of CycleGAN. Through model training and tuning, as well as data augmentation, we were able to achieve the best performance—both in terms of minimized loss and visual outputs—with a CycleGAN model. This challenge was originally presented as a Kaggle competition, and the final output results were sent to the submission page for evaluation and ranking, using the Memorization-informed Fréchet Inception Distance (MiFID) metric.

Kaggle competition link: https://www.kaggle.com/c/gan-getting-started  
