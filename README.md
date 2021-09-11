# To train
1. Replace the resized_images with your training dataset
2. Replace the resized_masks with your training masks
3. Replace the validation data accordingly. The name should be the same.
4. If you have more VRAM, you can increase the batch_size (which is now 2 for 4 GB VRAM equipped GPU), with appropriate size.
5. Change the epoch (now set 2 for testing purposes) according to your needs like 200 for example.

To train the model:
1. Download the zip file and extract it.
2. Use your anaconda or other python environment and go to that directory where train.py is located along with the dataset.
3. Execute the command on Command line interface: python train.py

This will train and save the weight file in the same directory as train.py
