## Pedestrian Detection
We plan to use [Caltech Pedestrian Dataset](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/index.html)
with [new annotations](http://www.vision.caltech.edu/Image_Datasets/CaltechPedestrians/index.html),
[CityPersons](https://bitbucket.org/shanshanzhang/citypersons) (a part of [CityScapes](https://www.cityscapes-dataset.com/)) and 
[KITTI](http://www.cvlibs.net/datasets/kitti/eval_object.php?obj_benchmark=2d) for benchmarking.

~~Besides, we found a more practical dataset [CUHK-SYSU Person Search Dataset](https://github.com/Dataset-VIPL-CAS/PSDBC).
We will also use this dataset for evaluation.~~ This dataset is not well annotated, many instances are missing. So we will not use it.

If you know some other good datasets, please inform us.

### Recent Update
* `2019.09.xx` model v1 for Caltech Pedestrian Dataset is released.

### Brief Introduction to Model Version
* v1 is designed for Caltech Pedestrian Dataset, covering pedestrian scale [xx, xx]. It has x branches.

### Accuracy on Caltech Pedestrian Dataset
After investigating the data, we found that Caltech Pedestrian Dataset is not well annotated, even giving the
new annotations (not annotated, not aligned well, the highly occluded are annotated). The final data used for training: 
1559 pos images (at least one pedestrian inside), 2691 neg images; 4786 pedestrian in total; the longer side
varies from 10 pixs to 500 pixs. 

#### Some Qualitative Results on Test Set
...