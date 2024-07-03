# AVF-Lip: High-Fidelity Talking Face Generation via Audio-Visual Fusion

<div align="center">

Mengduo Wu, Sirui Zhao*, Tong Wu, Yifan Xu, Tong Xu* <br>



University of Science and Technology of China, Hefei, China  


</div>


## Abstract
Talking face generation aims to create realistic facial videos with lips precisely synchronized to the input audio, finding broad applications in human-computer interaction, virtual avatars, and video conferencing. Despite significant advancements in previous works, existing methods continue to face challenges in achieving accurate lip synchronization and high visual quality. 
To address the above challenges, we propose a talking face generation framework named AVF-Lip that supports higher resolution and accurate lip synchronization. 
Specifically, an audio-visual fusion module (AVFM) is first customized to improve lip synchronization performance. This module aligns and integrates audio and visual features, fully leveraging the contextual information available in the audio.
Furthermore, we also introduce a dynamic and fine-grained face mask to improve lip synchronization.
Subsequently, to address the problem of lip distortion in high-resolution facial images, we design a set of loss functions based on face sketches to enhance the generation of the lip areas.
Extensive experiments demonstrate that our AVF-Lip outperforms state-of-the-art methods in lip synchronization and delivers competitive visual quality, positioning it as a promising solution for high-resolution and high-fidelity talking face generation.

## Pipeline

![framework-v6](https://github.com/wmd-1/avfm.github.io/assets/65806693/71f61f80-88cc-44fc-9dee-0442928f0a35)

## Quantitative Results

![quantitative results](https://github.com/wmd-1/avfm.github.io/assets/65806693/4fade20a-bb9c-427a-9714-6c5e19b70dcb)

## Quanlitative Results

### Our resulsts
<div align="center">

<video width="960" height="540" controls>
    <source src="Generation_M039_video_front_neutral_level_1_013.mp4" type="video/mp4">
</video>

<video width="720" height="576" controls>
    <source src="Generation_bbal5p.mp4" type="video/mp4">
</video>

</div>

### Qualitative comparisons with state-of-the-art methods on the MEAD and GRID datasets.

![case-mead-v4](https://github.com/wmd-1/wmd-1.github.io/assets/65806693/324dc38a-069d-411e-ac7b-593b56bf0d65)
![case-grid-v3](https://github.com/wmd-1/wmd-1.github.io/assets/65806693/23654141-5cf1-4e2f-a8aa-fc06cd97752a)


## Acknowledgement

This work was supported by the Young Scientists Fund of the Natural
Science Foundation of Sichuan Province (No.2023NSFSC1402) and grants
from the National Natural Science Foundation of China (No.61727809).
