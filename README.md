# Fast 3D Object Detection in the Wild

## Setup environment


## Download Dataset & Weights
Download the data folder and the weights folder from the link mentioned below - </br>

Dataset - Kitti.zip </br>
weights - checkpoints </br>

[Dataset and Weights](https://drive.google.com/drive/folders/1Msf2P5aSV1Xha-DPwiJ9K24v5gAdqxpG)

- Copy the dataset inside the Data folder of the cloned and built repository. And also create a folder named checkpoints and copy the weights.
 
## Evaluation
    ```shell
    python tools/test.py configs/pointpillars/hv_pointpillars_secfpn_6x8_160e_kitti-3d-car.py checkpoints/epoch_2.pth --show --show-dir ./data/kitti/show_results
    ```
