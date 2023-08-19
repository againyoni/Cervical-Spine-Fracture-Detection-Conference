# Cervical-Spine-Fracture-Detection-Conference
### Total processes on two-stage approach + corresponding ipynb notebook titles
1. preprocessing stage 1: windowing-preprocessing-technique-dataset.ipynb
2. stage 1 (multilabel): stage-1-window-multilabel.ipynb
3. preprocessing stage 2:
    - preprocess Yolov5: preprocess-cropping-vertebrae-with-yolo.ipynb
    - train Yolov5: train-infer-cropping-vertebrae-with-yolo.ipynb
    - Convert obtained Yolov5 output from jpg -> npz files. The output folders utilized in 'Cropping voxel': convert-to-npz-file-test-icon.ipynb
    - Cropping voxel, for processing vert_list.csv: stage2-preprocessing-sagittal-view-labels-only.ipynb
    - Cropping voxel: preprocessing-stage-2-cropping-voxel.ipynb
4. stage 2: stage-2-cracknet-lstm-yolo-window.ipynb


### Please check more visualizable total methodology from the pdf file attached
https://github.com/againyoni/Cervical-Spine-Fracture-Detection-Conference/blob/main/CSFD%20through%20Two-stage%20Approach%20of%20Mask%20Segmentation%20and%20Windowing%20based%20on%20Convolutional%20Neural%20Network.pdf

