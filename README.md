# cartoonize_you
Here we will use OpenCV to remove background from the image and cartoonize (Algorithm not finalized)
We will work with the images which sort of like selfie or person's chest to head image.

## Intial Research 

## For Background removal 

We can work with models like:
1. Unet [But it not good enough] https://arxiv.org/pdf/1505.04597.pdf 
2. Fully connected convulation neural network [even Bad as starting point] https://arxiv.org/abs/1411.4038 
3. Tiramisu [So far best model for background removal] https://arxiv.org/abs/1611.09326 

### Implementation of Tiramisu
https://files.fast.ai/part2/lesson14/

It is based on DesNet. To know more about it https://arxiv.org/pdf/1608.06993.pdf

#### Data Sets For training with Tiramisu (can accept 75% accuracy)

http://groups.csail.mit.edu/vision/datasets/ADE20K/
http://mscoco.org/
https://files.fast.ai/part2/lesson14/

As mentioned the images type required for this project we do not have work with tiramisu , OpenCV will do the job but do check it out.

bg_remove.ipyb: file removes the background form the image (We have to enter image path) and save it as output_path.



