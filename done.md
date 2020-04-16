# This file content all correction that done to run this repository

- change import into maskrcnn-benchmark.model_zoo.py like recommanded [hier](https://github.com/facebookresearch/maskrcnn-benchmark/pull/673/files#diff-1252846857806d2e6071bf2681a76631) : done.

-   change the link to downloaded weights file in to paths_catalog.py because the S3 bucket is no more availabe.

    Example: the following link

        https://s3-us-west-2.amazonaws.com/detectron/35858933/12_2017_baselines/e2e_mask_rcnn_R-50-FPN_1x.yaml.01_48_14.DzEQe4wC/output/train/coco_2014_train%3Acoco_2014_valminusminival/generalized_rcnn/model_final.pkl

        must become

        https://dl.fbaipublicfiles.com/detectron/35858933/12_2017_baselines/e2e_mask_rcnn_R-50-FPN_1x.yaml.01_48_14.DzEQe4wC/output/train/coco_2014_train%3Acoco_2014_valminusminival/generalized_rcnn/model_final.pkl
:done

- Change Imported Modul name to match new pytorch version: done