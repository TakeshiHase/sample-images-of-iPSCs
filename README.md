# sample-images-of-iPSCs
The repository contains sample iPSC images for classifier models to assess pluripotency (sample image datasets are available in sample_image_data.zip). The iPSC images are obtained under the four cell culture conditions (conditions 1, 2, 3 ,and 4).
For each condition, 200 iamges were obtained and arranged as shown in the Figure 1. 
Information of position for each image is embedded in the file name of the images, i.e.,  F0001 represents position information of an image file of A-02_F0001_T0020_Z0001.png and the image is placed in yellow highlighted position in the Figure 1.

![image](https://github.com/TakeshiHase/sample-images-of-iPSCs/assets/8033227/cd060e39-257e-4ddc-a5c6-f3627194d24a)
Figure 1. Arrangement of iPSC image files.


The sample images are sample input images for the following three models proposed in our paper (see ciation).

model i: One-class Cell-based Classification

model ii: One-class Tile-based Classification

model iii: Semi-supervised Classification

models i and iii require one imput image file, while model ii require four adjucent image files to assess pluripotency.
There are three datasets (dataset 1, 2, and 3) for each condition and each dataset contains four adjucent images to input for model i.
For example, dataset1 under condition1 contains four adjucent image files, A-02_F0001_T0020_Z0001.png, A-02_F0001_T0020_Z0002.png, A-02_F0001_T0020_Z0003.png, and A-02_F0001_T0020_Z0004.png.

## citations
Ryutaro Akiyoshi1†, Takeshi Hase2,3†, Mayuri Sathiyananthavel2,3, Samik Ghosh2, Hiroaki Kitano2 and Ayako Yachie2,3* (2024) Noninvasive, Label-free Image Approaches to Predict Multimodal Molecular Markers in Pluripotency Assessment. (submitted)

1.	Yokogawa Electric Corporation, 2-9-32 Nakacho, Musashino-shi, Tokyo, 180-8750, Japan
2.	The Systems Biology Institute, Saisei Ikedayama Bldg., 5-10-25, Higashi Gotanda, Shinagawa-ku, Tokyo 141-0022, Japan
3.	SBX BioSciences, Inc. 1111 West Georgia Street, 20th Floor, Vancouver, B.C, V6E 4G2, Canada
†  Equal contribution
* Corresponding author: yachie@sbx-biosci.com

