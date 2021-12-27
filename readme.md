# Image Based Lighting

Tommy Kimura

## Recovering HDR maps

### My LDR Images

<img src="./assets/my_data.png" />

### Sample LDR Images

<img src="./assets/original.png" />

### Naive HDR merging

#### My Naive HDR merging

<img src="assets/my_naive_hdr.png" style="zoom:100%"/>

#### Sample Naive HDR merging

<img src="assets/naive_hdr_image.png" style="zoom:30%"/>

<div style="page-break-after: always" />

### Weighted HDR merging

#### My Weighted HDR merging

<img src="./assets/my_weighted_hdr.png" />

#### Sample Weighted HDR merging

<img src="./assets/weighted_hdr_image.png" style="zoom:30%"/>

<div style="page-break-after: always" />

### Calibrated HDR merging

#### My Calibrated HDR merging

<img src = "./assets/my_estimated_hdr.png" />

#### Sample Calibrated HDR merging

<img src="assets/calibrated_hdr_image.png" style="zoom:30%"/>

#### Plots of G vs. Intensity and Intensity vs. G

#### My image graphs

<img src ="./assets/my_fvg.png" />

<img src = "./assets/my_gvf.png" />

#### Sample image graphs

<img src="./assets/fvg.png"/>

<img src="./assets/gvf.png" />

<div style="page-break-after: always" />

### Comparison & Error

<img src = "./assets/my_estimated_diff.png" />

|     Naive      |    Log Range=6.122     |   AVG RMS Error = 0.799   |
| :------------: | :--------------------: | :-----------------------: |
|  **WEIGHTED**  | **LOG RANGE = 6.387**  | **AVG RMS ERROR = 0.81**  |
| **CALIBRATED** | **LOG RANGE = 10.696** | **AVG RMS ERROR = 0.589** |

<img src = "./assets/linear_images.png" />

|     Naive      |   Log Range=6.464    |   AVG RMS Error= 0.324   |
| :------------: | :------------------: | :----------------------: |
|  **WEIGHTED**  | **LOG RANGE= 6.622** | **AVG RMS ERROR= 0.286** |
| **CALIBRATED** | **LOG RANGE= 7.002** | **AVG RMS ERROR= 0.255** |

### Panoramic transformations

#### My Panoramic

##### Normal

<img src = "./assets/my_normal.png"/>

##### Reflection

<img src="./assets/my_reflection.png" />

<div style="page-break-after: always" />

##### Final Result

<img src = "./assets/my_panoramic.png" />

#### Sample Panoramic

<img src = "./assets/panoramic.png" />

<div style="page-break-after: always" />

### Blender

#### Background

<img src = "./assets/background.png" />

<div style="page-break-after: always" />

#### Mask

<img src = "./assets/mask.png" />

<div style="page-break-after: always" />

#### With Object Image

<img src = "./assets/object.png" />

<div style="page-break-after: always" />

#### With out object image

<img src = "./assets/no_object.png" />

<div style="page-break-after: always" />

#### Final Result

<img src = "./assets/final.png" />

