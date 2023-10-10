# Retina-segmentation

The U-Net model has dramatically improved overall medical image segmentation. However, for retinal vessel segmentation, U-Net-based architectures face the problem of difficult recognition of fine vessels and loss of feature information due to low image contrast. So, to improve the recognition of capillaries and reduce the loss of vascular information, this project aims to do the following architectural modification and come up with a better result:

    1. Replace the original convolutional layer with the multi-scale residual atrous convolution and add multi-level residual atrous       
       spatial pyramid pooling modules between the encoding and decoding modules.
    2. Add a multi-channel attention mechanism at the short connection of the model
    3. Add a lightweight attention mechanism to the pooling layer using a convolutional block attention module. 
    

Note:- the Digital Retinal Image for Vessel Extraction (DRIVE) and Structure analysis of the Retina (STARE) datasets were used to do the task.

