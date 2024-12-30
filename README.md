# ContextVisionAI

This model was created with a U-Net model trained on a fashion MNIST dataset. Then, the model was extended with various functionalities including forward and reverse diffusion, group normalization, GELU activation function, rearrange pooling, sinusoidal position embeddings, classifier-free diffusion guidance (CFDG), and weighted reverse diffusion.

A Contrastive Language-Image Pre-Training (CLIP) model was also used to generate images from text and enhance the diffusion model with the CLIP encodings.

Finally, I used the diffusion model to generate images from the MNIST dataset which is similar to the fashion MNIST dataset and used a classifier enhanced with CFDG which was already trained on the MNIST to identify the images, obtaining 98% accuracy. Other performance metrics could be used but this is a start.

Screenshots:

![1](https://github.com/user-attachments/assets/3960d18b-1a4b-41ed-bd1e-19c0b2b2867a)

![2](https://github.com/user-attachments/assets/413b42a7-c603-42bb-9810-83d867f9b233)

![3](https://github.com/user-attachments/assets/6fed994f-6892-4e02-b4cb-55376c2ce47d)

![4](https://github.com/user-attachments/assets/e985179d-595a-4549-ba2e-da9fe562bc8b)

![5](https://github.com/user-attachments/assets/72ce8201-9787-4c78-8e9b-8510155b9fce)

![6](https://github.com/user-attachments/assets/a370d297-3c69-40bc-87ad-52f32ded39a1)

![7](https://github.com/user-attachments/assets/d5b98b5a-281b-45ef-a489-beef22eed4a2)






