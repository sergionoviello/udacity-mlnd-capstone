# Machine Learning Engineer Nanodegree
## Capstone Proposal

Sergio Noviello

September 25th, 2018


### Installation

The best way is to run the jupyter notebook with all the requirements installed is to use Docker.
In order to build the image please run:
```
docker build -t snov-capstone .
```

and to run the container:
```
docker run --rm -v $(pwd):/app -v $(pwd)/data:/app/data -it -p 8888:8888 snov-capstone
```

This project requires the train and test dataset available for download on Kaggle.com

### Train

https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/train.7z

### Train Additional Data
https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/additional_Type_1_v2.7z
https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/additional_Type_2_v2.7z
https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/additional_Type_3_v2.7z

### Test (stage1)

https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/test.7z

### Test (stage2)

https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/download/test.7z