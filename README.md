# Tsinghua-Dogs
Tsinghua Dogs is a fine-grained classification dataset for dogs, over 65% of whose images are collected from people's real life. Each dog breed in the dataset contains at least 200 images and a maximum of 7,449 images, basically in proportion to their frequency of occurrence in China, so it significantly increases the diversity for each breed over existing dataset (see Fig. 1). Furthermore, Tsinghua Dogs annotated bounding boxes of the dog’s whole body and head in each image (see Fig. 2), which can be used for supervising the training of learning algorithms as well as testing them.

Details about Tsinghua Dogs can be found in this [paper]("https://doi.org/10.1007/s41095-020-0184-6"). 

## Dataset

## Anotations

## Download

The dataset provides two versions of images to download: high resolution and low resolution.

## Benchmarking

| Rank | Model | Backbone | Batchsize | Epochs | Accuracy (%) | Year | 
|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|
| 1 | WS_DAN | 86.1 |
| 2 | TwoStream-anet2016 | 84.7  |
| 3 | TwoStream-incepv3 | 60.3 |
| 4 | TwoStream-anet2016 | 50.0 |

## Citing

Please cite our Tsinghua Dogs in your publications if it helps your research:
```BibTeX
@article{Zou2020ThuDogs,
  title={A new dataset of dog breed images and a benchmark for fine-grained classification},
  author={Zou, Ding-Nan and Zhang, Song-Hai and Mu, Tai-Jiang and Zhang, Min},
  booktitle={Computational Visual Media},
  year={2020},
  url={https://doi.org/10.1007/s41095-020-0184-6}
} 
```
