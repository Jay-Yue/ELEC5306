# ELEC5306

#Version
Python 3.6.9
Cuda 10.1

#Hyperparameters
lr = 1e-4
lr scheduler = [20 40 80] gamma = 0.5
batch_size = 7
decayrate = 0
optimizer = Adam

#model
type = DnCNN
depth = 10

#Final Results
PSNR = 33.79806373
PSNR_diff = 1.34248363
at Epoch = 100

#Test command
!python main_test.py --model_choice DnCNN --model_dir my_model_q40/project2.pth.tar # test my model
