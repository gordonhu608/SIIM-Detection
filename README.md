# siim-covid19-detection

# Train environment
1.pytorch==1.7.1

2.pytorch-lightning==1.3.3

# Prepare train and mask data
## 1 convert to png
$ run `siim_convert_to_png.ipynb`

## 2 convert to mask png
$ run `siim_convert_to_mask_png.ipynb`

## 3 generate folds
see `train_study_folds_washen_v2.csv` file.

# Train
$ run `bash train.sh` 

# Valid
$ run `siim_valid.ipynb`

# Predict
$ run `siim_predict.ipynb`
