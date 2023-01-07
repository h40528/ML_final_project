# ML_final_project

Model link: https://drive.google.com/drive/u/1/folders/1RQuymJleFRULtzlSPOUOtA6ah1onITu-

## Installation

Install the following package before running 
```sh
pip install -U scikit-learn # For Windows 64bit version of Python 3
pip install feature_engine
pip install imblearn
pip install gdown
```
## Train

Directly run 0816036_Final_train.ipynb

The model will be saved in the current directory.

## Inference

### Directly run 0816036_Final_inference.ipynb 

The pretrained models will be automatically downloaded via gdown

### Using models trained by 0816036_Final_train.ipynb

Create a directory called "saved_model" and move all the pretrained models into the directory.

Run 0816036_Final_inference.ipynb
