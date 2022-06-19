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
## Project Description:

My project was inspired by Helena Sarin's process and her application of CycleGAN in her own practice. While reading through the article assigned as a class reading, I remember thinking that I want to experiment just like that since I am an artist myself, a lettering artist to be more specific. When I first started working on my final project, I didn't know where to start as I did not have nearly enough data to train a GAN and I knew that I wanted to use my own lettering work as an input. My first step milestone in this project was to have enough data to be able to train any model. Therefore, I started with a StyleGAN2 ADA by Derrick Schultz since did not require as much data to train. I loaded around 20 sketches and prayed the model would work. It didn't. So, I sketched some more, and loaded 33 images and it worked. 

---
## Project Structure:

![Asset 1-100](https://user-images.githubusercontent.com/92052904/174483211-41665523-dce5-4ce3-bff3-31d625cc5381.jpg)

---

## Third Party Resources:

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

## Development and Process:
---
## Results and Evaluation:


