# Lin(林)3D: Large-scale forest scene INterpretation 3D point cloud dataset（current verison：v0.2）
* The utilization of Light Detection And Ranging (LiDAR) provides new insights into forest inventories due to its ability to efficiently and accurately capture the 3D structure of forests. Accurate interpretation of the massive LiDAR point cloud and segmentation of the point cloud into key forest components such as **foliage, wood (i.e., trunk, branch), ground, and lower objects (i.e., grass, shrubs)** allows accurate estimation of forest attributes. These attributes include total wood volume, tree hydraulics, leaf density, and leaf angle and arrangement, etc.
* Recent breakthroughs in supervised deep learning for 3D scene understanding provide potential solutions for addressing this issue. However, many studies have focused only on forest environments using their own data at small spatiotemporal scales and are restricted to specific ecosystems and sensor types.
* To fill this gap, we constructed perhaps the first large-scale forest semantic segmentation dataset. It includes over 100 tiles and covers over 40,000 m² of diverse typical ecosystems and forest types and was built upon point clouds collected by various types of sensors (ULS, TLS, ALS, BLS, etc.). Careful manual labelling was carried out by a group of trained students and experts.
* We will gradually open the dataset to the entire community to promote the development of 3D point cloud deep learning for forestry studies.
* At present, the dataset is still undergoing further revisions, and will continue to be updated here
# Data information of Lin3D v0.1 (update in 2023.9.5)
The data can be downloaded at https://drive.google.com/drive/folders/1r1yHiT9b21H1Nq8PXiduE6ZLrBu3D94w?usp=sharing

Lin3D v0.1 mainly contains annotated TLS point cloud TLS collected in GuangXi.

The point cloud data are stored in a .txt format file, which contain four elements: x y z label

For label meaning:

* 0:Ground

* 1:Lower objects

* 2:Wood

* 3:Foliage

![TLS LIN3dSHUJU](https://github.com/user-attachments/assets/eabe7dbb-b42e-4d49-8bd2-ac5f06cd98d4)

# Data information of Lin3D v0.2 (update in 2024.12.17)

The data can be downloaded at https://drive.google.com/file/d/1RevGwD7j18xX3-PDsUchTLUa5mAib3tx/view?usp=sharing

Lin3D v0.2 mainly updates annotated ULS point cloud used in our paper "Towards a point cloud understanding framework for forest scene semantic segmentation across forest types and sensor platforms".

The point cloud data are stored in a .txt format file, which contain four elements: x y z label

For label meaning:

* 0:Ground

* 1:Lower objects

* 2:Wood

* 3:Foliage


![ULS lin3d_vis](https://github.com/user-attachments/assets/96795196-701c-4f48-b720-be7dd4190c28)

# Citation
