# cleaned-DukeMTMC-reID
Cleaned test data list of DukeMTMC-reID released with our paper accepted by ICCV 2021: Learning Instance-level Spatial-Temporal Patterns for Person Re-identification

## Two kinds of samples are eliminated from the test set of DukeMTMC-reID:

### 1. The samples with wrong labels, sunch as: 

![arch](wrong_labels.png)

### 2. The samples in which the pedestrian is completely occluded, such as: 

![arch](occlusion.png)

## Cleaned database

The data of DukeMTMC-reID can be found [here](http://vision.cs.duke.edu/DukeMTMC/).

The query list of cleaned test database is `query_cleaned.txt`

The gallery list of cleaned test database is `gallery_cleaned.txt`

# Citation
If you find our cleaned database useful in your research, please consider to cite:

    @inproceedings{ren2021learning,
      author={Ren, Min and He, Lingxiao and Liao, Xingyu and Liu, Wu and Wang, Yunlong and Tan, Tieniu},
      title={Learning Instance-level Spatial-Temporal Patterns for Person Re-identification},
      booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
      year={2021}
    }
    
