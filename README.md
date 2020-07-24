![image](https://github.com/jinsel/Text-to-Image-Generation/blob/master/images/bird.jpeg)
# Text-to-Image-Generation
In this project, we are Generate the Images from Text Description using the Stack GANs(SGANs).<br> And also we are using the pytorch framework for this project<br>
Stacked Generative Adversarial Networks To generate high-resolution images with photo-realistic details<br> <b>It decomposes the text-to-image generative process into two stages: </b><br>
<b>Stage-I GAN:</b> it sketches the primitive shape and ba-sic colors of the object conditioned on the given textdescription, and draws the background layout from arandom noise vector, yielding a low-resolution image.<br> 
<b>Stage-II GAN:</b> it corrects defects in the low-resolutionimage from Stage-I and completes details of the objectby reading the text description again, producing a high-resolution photo-realistic image.

## Basic of Stacked Generative Adversarial Networks (SGAN)
![image](https://github.com/jinsel/Text-to-Image-Generation/blob/master/images/stack%20gans.png)
https://arxiv.org/abs/1612.04357 <br>
https://medium.com/@jonathan_hui/gan-stacked-generative-adversarial-networks-sgan-d9449ac63db8

## Architecture of Text-to-Image Generation
![image](https://github.com/jinsel/Text-to-Image-Generation/blob/master/images/archtecture.jpg)
