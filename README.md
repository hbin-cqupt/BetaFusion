# About BetaFusion
_BetaFusion_ is a multi-focus image dataset, which contains 20 image pairs.

The all images are collected with an Sony ILCE6000 camera, and the images are well registered.

# Raw data
We also provide the source images with key parameters, see [GoogleDrive](https://drive.google.com/file/d/1p6LeaNJf6F6qqi96Cyvm93Nql3DVKQ2o/view?usp=sharing)

the raw data are named as: seq\_\[a|b|c|d\]\_distance\_aperture.jpg.

seq is the sequence of the image, 

"a|b|c|d" refers to different focus situation:
- a: near-focus, big aperture
- b: near-focus, small aperture
- c: far-focus, big aperture
- d: far-focus, small aperture

"distance" is the distance between focus point and the camera,

"aperture" is the aperture used when taking the photo.

# citation
If you think our dataset is helpful to you, you can consider citing our work:
@inproceedings{focus_stacking,
	title = Focus Stacking with High Fidelity and Superior Visual Effects,
	booktitle = {Proceedings of the {AAAI} {Conference} on {Artificial} {Intelligence}},
	author = {Bo Liu, Bin Hu, Xiuli Bi, Weisheng Li, Bin Xiao}
}
