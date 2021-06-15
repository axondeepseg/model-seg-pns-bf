# model-seg-pns-bf
default OM model that works at a resolution of 0.1 micrometer per pixel

# Steps to train this model
1. Get ADS version: [[5af8cbb]](https://github.com/neuropoly/axondeepseg/commit/5af8cbb1e782092ac46e0586eca0f827c0eff938)
2. Get the data: Available at NeuroPoly lab in 
```
duke/projects/axondeepseg/20201016_model_seg_pns_bf/10_model_selected/dataset_training/dataset_patches/20210121_training_gps_01_filtered
```
4. Run the "02-training_guideline-pns.ipynb" notebook available at NeuroPoly lab in 
```
duke/projects/axondeepseg/20201016_model_seg_pns_bf/10_model_selected/notebooks
```
6. After successfully running all the cells, the trained model file will be saved under the directory: AxonDeepSeg/axondeepseg/models/
