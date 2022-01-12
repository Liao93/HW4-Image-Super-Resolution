# HW4-Image-Super-Resolution

## Inference
Run 'inference.ipynb'.
### Environment
- Python 3.7.12
- torch 1.10.0+cu111
- torchvision 0.11.1+cu111
- Pillow 7.1.2

### Input
You can modify the path on your own machine.
- 'datasets.zip': including the testing images. It should be at the working directory in default.
- 'dataroot': this code runs on Colab, so the testing data will be at '/content/datasets/testing_lr_images' after being unzipped.
- 'SR_model.pkl': the pre-trained model. In default, the file should be moved to the working directory. Download link: https://drive.google.com/file/d/1IX-6Zks7ChNWkitgHxW6NxbPGttLOmVz/view?usp=sharing 

### Output
You can modify the path on your own machine.
- All the reconstructed high-resolution images. In default, they will be at the working directory.
