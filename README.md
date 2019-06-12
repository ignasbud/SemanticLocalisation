# Semantic Localisation via Globally Unique Instance Segmenation

This project provides the implementation of label propagation of Budvytis et. al, **Large scale labelled video data augmentation for semantic segmentation in driving scenarios.** *In ICCV Workshop track, Venice, October 2017 [1].*

[paper](http://mi.eng.cam.ac.uk/~ib255/files/Budvytis_et_al_BMVC18_Semantic_Localisation.pdf)

You can find more related research [here](http://mi.eng.cam.ac.uk/~ib255/).

**Semantic localisation in CamVid-360 dataset:**
 <img src="http://mi.eng.cam.ac.uk/~ib255/files/external/semantic_localisation_camvid360.gif" data-canonical-src="http://mi.eng.cam.ac.uk/~ib255/files/external/semantic_localisation_camvid360.gif" width="100%" />
 
**Semantic localisation in an artificial city (SceneCity) with missing buildings:**
 <img src="http://mi.eng.cam.ac.uk/~ib255/files/external/semantic_localisation_scenecity_small.gif" data-canonical-src="http://mi.eng.cam.ac.uk/~ib255/files/external/semantic_localisation_scenecity_small.gif" width="100%" />

## Datasets

### CamVid-360 dataset

[Available up on e-mail.]

### SceneCity dataset


#### Images
The whole artificial city dataset can be downloaded [here](https://drive.google.com/open?id=1Gke_soseXkKmTuGH_QPk_drX2n84cApT).

- [SceneCity Small - Training data](https://drive.google.com/open?id=1sK3uftByg9Ct1HXkV9DiGAXZFqa-RE9P)
- [SceneCity Small - Test data](https://drive.google.com/open?id=1xC7RU9Ll9uojBE_-kCK9-DE3LtUUHXAR)
- [SceneCity Small Missing Buildings - Test data](https://drive.google.com/open?id=1I2u_fVAjNaq4G8p_pLCseHCVMq3d5bdN)
- [SceneCity Large - Training data](https://drive.google.com/open?id=1g2WEzDbcnIdcflmNAgF7vJOo3ZzS3dcv)
- [SceneCity Large - Test data](https://drive.google.com/open?id=1WDQDrfLKOgn-WC9Ot4lVDxRBmC-6NUkE)


#### Blender files

- **SceneCity Small** - The blender file for SceneCity Small map can be downloaded from [here](http://rpg.ifi.uzh.ch/fov.html). You can find more details about it in the work of Zhang et al [2].
- **SceneCity Small - Missing Buildings** - To be provided.
- **SceneCity Large** - To be provided.

#### Camera Trajectories

- **SceneCity Small** - [Camera trajectories for training data](./data/trajectories/SceneCity_Small_train_camera_info_2019_Jun_12.txt) used in Blender. Note that the original camera trajectory of [2] was used for test sequence. It was sampled at every 10 frames resulting in 300 frames out of 3000.
- **SceneCity Small - Missing Buildings** - Identical camera trajectories were used as for SceneCity Small for both train and test trajectories.
- **SceneCity Large** - To be provided.

## Getting Started

Instructions below explain prerequisites and installation steps needed.

### Prerequisites

[TO BE CONFIRMED]
<!---
- Python2.7
- numpy
- OpenCV3.4.1
-->

## Running the code

[TO BE CONFIRMED]

## Comments on reproducability of [1]

This code is a close, but not an identical replica of the code used in [1]. Explanations of the differences may be added in the future.

## TO-DO List

- Add code
- Add datasets
- Add a more detailed explation of different parts of the algorithms.
- [TBC]

## Citations

If you use this code please cite the following publications:

```
@InProceedings{SemanticLocalisation2018BMVC,
               author = {Budvytis, I. and Sauer, P. and Cipolla, R.},
               title = {Semantic localisation via globally unique instance segmentation},
               booktitle = {British Machine Vision Conference (BMVC), Newcastle},
               month = {September},
               year = {2018}                         
}

```

## References

[1] Budvytis, I., Sauer, P., Cipolla, R., 
**Semantic localisation via globally unique instance segmentation.** *In Proc. British Machine Vision Conference (BMVC), Newcastle, September 2018* 

[2] Zhang, Z., Rebecq, H., Forster, C., Scaramuzza, D.,
**Benefit of large field-of-view cameras for visual odometry.** *In Proc. IEEE International Conference on Robotics and Automation (ICRA), Stockholm, May 2016* 
