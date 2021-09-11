# About this project

This was a project created to experiment with machine learning and GAN image processing.

Unfortunately I don't have an nvidia gpu and AMDs support for machine learning is next to none.

What I did was train the model with images of myself and with the help of a discriminator running on my cpu. I had to utilize checkpoints since training a neural network on a CPU alone does take some time

Here are some of the best results that I have gotten from my neural net

![generated_img_000_2+new111](https://user-images.githubusercontent.com/24516988/132960699-7c7dff24-3ad3-4257-bb82-5f83c59f0fa7.png)
![generated_img_003_1+new111](https://user-images.githubusercontent.com/24516988/132960703-a1a3c487-4be0-442e-b573-bd83c2b992de.png)
![generated_img_006_4+new111](https://user-images.githubusercontent.com/24516988/132960707-8d34206f-5302-40cb-8af4-3787e6ab062b.png)


Once tensorflow and AMD start supporting their 6800xt lineup i will definately be revisiting this project and experimenting with other types of machine learning branches and push the limits of what can be done

# If you would like to try this project for yourself you will need to install

* TENSORFLOW

* KERAS

and create 3 directories in the root of the project

* **training_dataset/images** -- you will put all of your images in this directory

* **training_model/checkpoint** -- this will be your checkpoint directory

* **created/images/** -- this will be where all of the gererated images end up after each epoch cycle


if you are struggling to the the program to run, take a look at the official documentation here https://www.tensorflow.org/tutorials/generative/dcgan

