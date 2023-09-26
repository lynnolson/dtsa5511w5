# dtsa5511w5
Boulder MSDS DTSA5511 Week 5 Assignment

<!-- ABOUT THE PROJECT -->
## About the assignment
This project applies CycleGANS to learn how to transfer Monet's painting style to photos. It's the Kaggle task [I’m Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started)

### Dependencies

The code was developed with Python 3.10.4 and PyTorch and the following libraries and versions:

- numpy==1.24.3
- pandas==2.0.3
- skimage==0.21.0
- sklearn==1.3.0
- torch==2.0.1+cu117
- torchvision==0.15.2+cu117


The full environment setting can be installed through:
```
conda env create -f conda-environment.yaml
conda activate msds
```

### Data

The [data][https://www.kaggle.com/competitions/histopathologic-cancer-detection/data](https://www.kaggle.com/competitions/gan-getting-started/data) is available through Kaggle.

### Usage

All code may be found and run in the notebook gans_neural_transfer.ipynb.  The notebook assumes you have downloaded the Kaggle data and have the photo_jpg and monet_jpg directories.  The models were trained on a A100 GPU with 48GB of memory. They can be trained on something smaller but still would need a GPU (ideally something better than the P100 Kaggle provides for free though.)  I also load all images into memory for speed.


