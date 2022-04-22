# simple_unet
A TensorFlow Implementation of Simple U-Net architecture

This code provides an impelementation of classic U-Net architecture by Ronneberger et al. for image segmentation on Oxford Pet Dataset.

Download the repository and the Oxford-IIIT Pet Dataset. You can download the dataset and the annotations from the following link

https://www.robots.ox.ac.uk/~vgg/data/pets/

The structure of the directory should be as follows:

simple_unet  
|--annotations  
---|--trimaps  
---|--|--._Abyssinian_1.png 

---|--xmls  
|--images  
---|--Abyssinian_1.jpg  
|--network_arch.py  
|--train_u_net_simple.py  
|--utils.py

Make sure you install all the necessary packages such as tensorflow, keras, pillow, pandas, numpy  

While accessing the root directory from windows prompt or anaconda prompt type the following command  

python train_u_net_simple.py  

to train the network. Once the network is trained, the later half of the code will let you visualize the predictions on the validation set. 

Experimental Results  
Original Image ![image](https://user-images.githubusercontent.com/26203136/164710745-6c47fb97-1dd8-4306-846b-6823536bef67.png)
Ground Truth ![image](https://user-images.githubusercontent.com/26203136/164710771-7666fb0d-2d2e-457d-b0d6-85a3986c36a6.png)
Segmented Image (160,160) ![image](https://user-images.githubusercontent.com/26203136/164710793-7b0d0612-1397-4d1c-87fb-492002bb0a93.png)

Original Image ![image](https://user-images.githubusercontent.com/26203136/164710893-2885c078-ec28-4705-b9a2-296027a886f3.png)
Ground Truth ![image](https://user-images.githubusercontent.com/26203136/164710920-bc81af07-ff7e-4211-a2f5-2a9e811d0b9f.png)
Segmented Image (160,160) ![image](https://user-images.githubusercontent.com/26203136/164710946-8ed236a2-7ef2-417c-b2b6-f8b7dae2a507.png)



