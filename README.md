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

### Background removed by OpenCV

<img width="209" alt="Screenshot 2021-03-23 at 3 29 31 PM" src="https://user-images.githubusercontent.com/62153950/112128683-ab744a80-8bec-11eb-81bd-3c6dcbc01d01.png"> <img width="351" alt="Screenshot 2021-03-23 at 3 28 15 PM" src="https://user-images.githubusercontent.com/62153950/112128958-efffe600-8bec-11eb-9d97-1d90e54eb4cb.png"> <img width="357" alt="Screenshot 2021-03-23 at 3 26 18 PM" src="https://user-images.githubusercontent.com/62153950/112129009-f7bf8a80-8bec-11eb-9b90-6c1a99aedc18.png"><img width="362" alt="Screenshot 2021-03-23 at 3 27 36 PM" src="https://user-images.githubusercontent.com/62153950/112129041-0017c580-8bed-11eb-993f-9f5c47d615a2.png">

