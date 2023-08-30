# Lin(林)3D: Large-scale forest scene INterpretation 3D point cloud dataset
* The utilization of Light Detection And Ranging (LiDAR) provides new insights into forest inventories due to its ability to efficiently and accurately capture the 3D structure of forests. Accurate interpretation of the massive LiDAR point cloud and segmentation of the point cloud into key forest components such as **foliage, wood (i.e., trunk, branch), ground, and lower objects (i.e., grass, shrubs)** allows accurate estimation of forest attributes. These attributes include total wood volume, tree hydraulics, leaf density, and leaf angle and arrangement, etc.
* Recent breakthroughs in supervised deep learning for 3D scene understanding provide potential solutions for addressing this issue. However, many studies have focused only on forest environments using their own data at small spatiotemporal scales and are restricted to specific ecosystems and sensor types.
* To fill this gap, we constructed perhaps the first large-scale forest semantic segmentation dataset. It includes over 100 tiles and covers over 40,000 m² of diverse typical ecosystems and forest types and was built upon point clouds collected by various types of sensors (ULS, TLS, ALS, BLS, etc.). Careful manual labelling was carried out by a group of trained students and experts.
* We will gradually open the dataset to the entire community to promote the development of 3D point cloud deep learning for forestry studies.
* At present, the data set is still undergoing further revisions, and will continue to be updated here
# Data information
The point cloud data was stored as txt format. The txt file contains four elements: x y z label

For label meaning:

* 0:ground

* 1:lower objects

* 2:wood

* 3:foliage
![数据展示](https://github.com/bjfu-lidar/large-scale-forest-semantic-segmentation-dataset/assets/117680229/770e68e5-183f-4f3e-ba3a-580da686e2a8)
