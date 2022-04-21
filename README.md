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
