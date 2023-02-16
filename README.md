# Fake_thermal_image_generator
Creating fake thermal images using CycleGAN

Hello everyone, in this experimental project, I tried to obtain the estimation and synthetic thermal outputs of RGB highway images. I trained the CycleGAN model using the FLIR dataset. As a result, from any highway image, we can obtain an artificial thermal output of that image. Of course, this does not work with one hundred percent accuracy, but the car creates the sky and approximate highway boundaries mostly correctly.

Checkpoints are available at: https://disk.yandex.com.tr/d/sNRfwwXL0bGTfA
Main model: https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix
