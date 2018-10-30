#added by chen cheng
in training folder there are two python file, prepareData.py and train.py
#data preprocessing
We need to first generate the training data
1. modify DATA_PATH point to the folder that contain the correct protein-ligand complexes.
2. modify H5_PATH point to the folder that you want to save the 3D image h5 file
3. python prepareData.py
#training phase
1. for first time training, config LOAD_TRAIN to False; you can config LOAD_TRAIN to True if you just want to evaluation the model
2. config MULTIPLE_GPU to False(default) if you want to use single GPU for training.
3. EPOCH_SIZE indicate how many phases you would like to train the model.
4. python train.py
