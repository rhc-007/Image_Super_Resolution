low_res.ipynb: Generates low-resolution training images from the DIV2K high-resolution dataset using bicubic downsampling.

srcnn.ipynb: Trains the SRCNN model for 2× image super-resolution using patch-based learning on the DIV2K dataset.

espcn.ipynb: Trains the ESPCN model for 2× image super-resolution using sub-pixel convolution (pixel shuffle) for efficient upscaling.

srresnet.ipynb: Trains the SRResNet model for 2× image super-resolution using deep residual blocks to enhance perceptual image detail.

output.ipynb: Loads the trained SRCNN, ESPCN, and SRResNet models and visualizes side-by-side super-resolution results on sample validation images for comparison.

srcnn_epoch20.pth: Trained SRCNN model weights after 20 epochs (used for 2× super-resolution inference).

espcn_epoch20.pth: Trained ESPCN model weights after 20 epochs (used for 2× super-resolution inference).

srresnet_epoch20.pth: Trained SRResNet model weights after 20 epochs (used for 2× super-resolution inference).
