# DefectNet
Complete workflow for locating atomic defects in electron microscopy movies using only a single movie frame for generation of a training set. This is based on the idea described originally in our paper npj Computational Materials 5, 12 (2019), but now with the updated augmentation procedure (includes adding noise, zoom-in and flip/rotations) and using PyTorch instead of Keras for model training/predictions. See notebook DefectSniffer.ipynb, which should be opened and executed in Google Colab. The augmentation procedure introduced here should be applicable to other types of data (including manually labeled image-groundtruth pairs).