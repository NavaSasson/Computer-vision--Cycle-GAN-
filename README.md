# Computer-vision-graduation-project
Face swap: The goal is to transfer my face to another domain using deep learning based computer vision and complex neural networks (Cycle GAN).

My project was to training the cycle Gan model using this open source: 
https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix
The goal of the project: Live Generation –
A person (me) looks at the camera and the model will know how to use what he learned and to 
generate the person(me) to Red Riding Hood (me with a hat of red riding hood).

I'm using the Cycle GAN model. Cycle GAN is a type of Generative Adversarial Network (GAN) that 
aims to learn mappings between two different domains (A and B) without requiring paired examples.
Throughout the training, the generator produces fake images that are increasingly like to reality so 
that the discriminator has difficulty identifying and differentiating between them. 
In addition, using the open source helped me and made the job easier, more than writing generation 
code for the model myself.
All the advantages above (and the lecturer's recommendation) made me choose this model.
This model easily learned my dataset and managed to generate after 79 epochs successful images
(and in the live test 110 epochs)

![pic1](https://github.com/NavaSasson/Computer-vision-graduation-project/blob/main/Example%20of%20photos%20during%20training.png)


