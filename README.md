# Two-stage contrastive learning for unsupervised visible-infrared person re-identification
The paper was submitted to JEI
## Datasets Download
The datasets preprocessed can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1TJG3TRgqi_DUMItJeFU4285IaB10-cXl).
## Training

SYSU-MM01:

1. Train:
```shell
python regdb_train.py -b 256 -a agw -d  regdb_rgb --iters 100 --momentum 0.1 --eps 0.6 --num-instances 16
```


2. Test:
```shell
python sysu_test.py -b 256 -a agw -d  sysu_all --iters 200 --momentum 0.1 --eps 0.6 --num-instances 16
```

