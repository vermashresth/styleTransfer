# styleTransfer
Practice Implementation of Neural style transfer using PyTorch.

Needs two images, a style image and a content image. Change path for both files accordingly in `style.py` (`style_img` and `content_img` variables.)

We aggregate content loss and style loss (using gram matrix) at every feature layer in VGG and minimize both loss. Thus the outcome of the the style transfer is an image which is close to 
`content_img` content wise and `style_img` style wise. 

Requirements:
- Pytorch
- PIL
- OpenCv
