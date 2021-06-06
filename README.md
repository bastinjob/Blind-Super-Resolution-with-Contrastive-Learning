# IIST_Final_Year_Project
Extracting Abstract Degradation Representationthrough Contrastive Learning for BlindSuper-Resolution and Denoising
Environment Specs : Only on Linux operating system

1. Python = 3.5+
2. Pytorch = 0.1.8
3. open-cv
4. skimage
5. numpy
6. matplotlib
7. imageio
8. scipy

This repository has three version of the project. 
1. Built_from_Scratch.ipynb is our original work of a low utility version of the project
2. Moco-version is the original work of DASR network
3. SimCLR-version is our improvement to the existing method.


With the recent advancement in Contrastive learning, we explore and investigate a new
approach towards degradation learning based architectures. Instead of estimating the degra-
dation from LR image, we explore the possibility of extracting an abstract representation
of degradation from an image, to distinguish from the latent degradation of another im-
age. This abstract degradation representation will then be used in Super resolving the LR
image. This approach does not require direct supervision from a predefined degradation.
Moreover, learning abstract representation of the degradation is easier and effective than
learning full representation of the degradation. Thus, this approach is aimed towards nov-
elty and efficiency in Single image Super Resolution task.
