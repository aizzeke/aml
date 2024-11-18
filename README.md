#### Here is Python snippet for downloading a dataset on your project

#### Install the Kaggle API if not done already:

pip install kaggle

import kaggle

#### Set your Kaggle API credentials if needed
#### You should have your 'kaggle.json' file from your Kaggle account.

#### Download the dataset

kaggle.api.dataset_download_files('sumn2u/garbage-classification-v2', path='path_to_save', unzip=True)

#### This will download the dataset and unzip it into the specified path.
