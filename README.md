# Advanced Coding 3: Exploring Machine Intelligence <br> Final Project | Sali Mallat | 20040127

---

## Table of Contents

  - [Video Documentation](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#video-documentation)
  - [Project Description](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#project-description)
  - [Project Structure](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#project-structure)
  - [Third Party Resources](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#third-party-resources)
  - [Development and Process](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#development-and-process)
  - [Results and Evaluation](https://github.com/s-mallat/FinalProject_AdvCoding3/blob/main/README.md#results-and-evaluation)

---

## Video Documentation:
---
## Project Description

My project was inspired by Helena Sarin's process and her application of CycleGAN in her own practice. From the moment I read the article on Sarin's work, I knew that I wanted to use my own lettering/calligraphy work as a dataset in my final project, even before deciding on which model or ML library to use. The purpose of my project is purely experimental, as I use two different GAN models (StyleGAN2 ADA using Tensorflow and CycleGAN using Pytorch) to generate images. Throughout this process, I encountered so many challenges starting from the fact that I didn't have nearly enough data to train any model. As a versatile artist, my work doesn't follow a specific style or pattern, and that meant that I had to start drawing my own dataset. Soon, I realized that that plan was too exhausting and time-consuming, so I opted for different approach. 

I decided to load my small dataset of 33 images into a StyleGAN2 ADA model that didn't require a large dataset to train. My aim was to train the model so that it can generate the new dataset for me and hopefully that would allow me to avoid drawing hundreds of images. After a long process of trial and error, my new dataset was finally generated from the StyleGAN2 ADA model. 

My next step was loading the new dataset into a CycleGAN model and applying a style transfer. Since I already had the Animal Faces dataset from Kaggle downloaded on my machine, I chose to use it for the style transfer. My intention wasn't to turn animal faces to black and white high contrast images similar to that of the calligraphy images, but rather to transfer the three dimensionality of photography to flat two dimensional calligraphy strokes. 

I would say that I learnt a lot through this project, as I initially was unsure how to even load my own dataset or tweak the existing code and debug any issues I encountered. Eventually however, I became comfortable enough to not just load a dataset, but to use multiple GAN models that use different machine learning libraries and successfully generate images from them.


---
## Project Structure

![Asset 1-100](https://user-images.githubusercontent.com/92052904/174483211-41665523-dce5-4ce3-bff3-31d625cc5381.jpg)

---

## Third Party Resources

### Attributions
For this project, I used two pre-existing colab Notebooks, StyleGAN2 ADA attributed to Derrick Schultz and NVIDIA, and CycleGAN-pix2pix adaptation attributed to Jun-Yan Zhu and Taesung Park. I included a copy of each notebook's license in this Github repo, as well as an attribution section at the top of each colab notebook. Furthermore, I have also used other third party code which I reference when used in the colab code block itself.

### What I Changed
I tweaked and modified the existing colab notebooks to suit the nature of my project. As someone who doesn't have an extensive knowledge of python, I did resort to google and forums for most of the changes I wanted to apply. Therefore, there is a lot of third party code which I have taken the length to understand in order to modify accordingly and make sure users don't run into errors while using these notebooks.

  
| Notebooks  | Reference | Original |
| ------------- | ------------- |------------- |
| StyleGAN2 ADA Notebook  | Copyright (c) 2020, NVIDIA Corporation. All rights reserved. NVIDIA Source Code License for StyleGAN2 with Adaptive Discriminator Augmentation (ADA)  | https://github.com/dvschultz/stylegan2-ada  |
| CycleGAN-Pix2Pix Notebook  | Copyright (c) 2017, Jun-Yan Zhu and Taesung Park. All rights reserved.  | https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix  |

| Dataset | Reference |
| ------- | --------- |
| Calligraphy | Created by me |
| AFHQ | Kaggle (https://www.kaggle.com/datasets/andrewmvd/animal-faces) |

| Other References  |
| ---------- |
| https://stackoverflow.com/questions/69986297/what-is-the-nvidia-smi-command-do  |
| https://exerror.com/notimplementederror-cannot-convert-a-symbolic-tensor-2nd_target0-to-a-numpy-array/ |
| https://stackoverflow.com/questions/1855095/how-to-create-a-zip-archive-of-a-directory |
| https://stackoverflow.com/questions/50453428/how-do-i-download-multiple-files-or-an-entire-folder-from-google-colab |
| https://www.guru99.com/python-rename-file.html |
| https://www.geeksforgeeks.org/create-a-directory-in-python/ |
| https://stackoverflow.com/questions/123198/how-to-copy-files | 
| https://www.geeksforgeeks.org/rename-multiple-files-using-python/ |
| https://www.geeksforgeeks.org/how-to-display-multiple-images-in-one-figure-correctly-in-matplotlib/ | 
| https://kanoki.org/2021/05/11/show-images-in-grid-inside-jupyter-notebook-using-matplotlib-and-numpy/ |
| https://colab.research.google.com/github/jasper-zheng/colab-snippets/blob/main/aw_code_snippets.ipynb#scrollTo=h5RmA9ywA4a- |
| https://stackoverflow.com/questions/1274405/how-to-create-new-folder |
| https://colab.research.google.com/drive/1AG19IKJ_J28-LjjOo2ntY1uLsMDHEuAs#scrollTo=N2RBLT6rYBAJ | 
| https://www.behance.net/gallery/8297685/Rurubu |

---

## Development and Process
### StyleGAN2 ADA

https://user-images.githubusercontent.com/92052904/174496754-c30aa7bd-715a-49e2-a522-840d0c797597.mp4

---
### CycleGAN

![Asset 2-100](https://user-images.githubusercontent.com/92052904/174496201-9e0f6fff-dce0-44f6-b958-b211f399b456.jpg)

https://user-images.githubusercontent.com/92052904/174496257-c1f34872-e415-45ca-9032-8e476feb1cb4.mp4

https://user-images.githubusercontent.com/92052904/174496270-4b4db1de-8163-41ff-9736-2a580ab31788.mp4

![Unknown-7](https://user-images.githubusercontent.com/92052904/174496162-064afaf9-1f4c-4d92-9cb4-dc555eb65eef.png)

---
## Results and Evaluation

The end-results of this experimental project were somewhat surprising, mostly because I really did start with not even knowing how to properly load a external dataset. So, I would say that I'm very happy and impressed with the final outcome. I've attempted to load all sorts of images to test this newly trained model, from calligraphy to nature photography. I've noticed that this model generates really interesting images from high contrast input with a light background. This is not surprising since the original dataset used ultilizes black ink calligraphy on a white background. On the other hand, the generated images for input with low contrast is somewhat less impressive and just adds a layer of color, noise, and vintage to the original.
Final Dataset generated from StyleGAN2 ADA

https://user-images.githubusercontent.com/92052904/174496687-6f9b039f-9324-48e7-b57c-99e5b42ead82.mp4

Final Style Transfer weights used for the CycleGAN

![Unknown-8](https://user-images.githubusercontent.com/92052904/174496344-09830e7b-1685-43bb-8188-83037238c6ba.png)
![Unknown-9](https://user-images.githubusercontent.com/92052904/174496353-c62574c7-ea1d-4813-98fb-5d32a5cb4c95.png)
