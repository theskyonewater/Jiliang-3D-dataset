# Jiliang-3D: A Large-Scale Urban Outdoor Point Cloud Dataset

# Introduction of the Jiliang-3D datasets
The Jiliang-3D dateset is a large-scale urban outdoor point cloud dateset built by Hexagon Laboratory, China Jiliang University. Based on the analysis of the existing problems in the current large-scale point cloud datasets, our aim is to enrich the large-scale outdoor point cloud datasets and the diversity of static point cloud data.

It conducts oblique photography on campus through the DJI Mavic 3E drone, and then performs three-dimensional point cloud reconstruction to generate point cloud data. The collection area covers approximately 320,000 square meters.

This data is mainly used to test the performance of semantic segmentation algorithms for large-scale cities' scenes. The data acquisition area scenes are complex and varied, including parking lots, small squares, lawns, dormitory buildings, experimental buildings, and other scenes. The shape of each building is different, there is a certain degree of shielding between the building and the vegetation, and the density of the point cloud varies greatly. To facilitate the training and testing of the network model, the entire model is divided into 10 regions, and the performance of the model is evaluated by selecting different regions with diverse scenarios. The entire point cloud dataset and its division are shown in Figure 1

<img width="782" height="498" alt="image" src="https://github.com/user-attachments/assets/61840711-c40f-424a-be85-0379462fa92f" />

Figure 1 Regional division of Jiliang-3D dataset

# Point cloud semantic labeling
Data labeling is done manually with CloudCompare software. The basic principle of manual semantic annotation is that each category has a precise meaning and can be used for practical value, such as urban planning and asset management.Following the labeling schema of comparable datasets like SensatUrban，ground objects are mainly divided into night categories.Figure 2 shows nine categories

1) Bike: Bicycles and electric scooters parked along roadsides or in parking areas.
2)	Building: Mostly man-made structures, including dormitories, academic buildings, etc.
3)	Cars: Automobiles parked along roads or in designated parking spaces.
4)	Clutter: Includes parasols, bulletin boards, signs, and other man-made miscellaneous structures.
5)	Grass: Grass-covered ground surfaces.
6)	Poles: Lamp posts and similar vertical structures.
7)	Roads: Man-made paved roadways.
8)	Vegetation: Trees, large shrubs, or small bushes.
9)	Water: Water surfaces such as ponds or canals.

<img width="691" height="544" alt="image" src="https://github.com/user-attachments/assets/5b89eb19-8007-4efe-ba86-f186bcbaaa69" />

Figure 2 Different classifications in the Jiliang-3D dataset

# Distribution of the scene categories
The Jiliang-3D dataset consists primarily of buildings, vegetation, and impervious surface, which fits the characteristics of urban scenes. At the same time, the dataset also contains essential elements of urban scenes such as cars, bicycles, and pedestrians, which can better simulate the urban environment. The Jiliang-3D dataset has certain advantages for point cloud semantic segmentation of city environments. From the semantic segmentation perspective of the large-scale point cloud, the Jiliang-3D dataset can play an excellent complementary role in understanding the point cloud semantics of the city scenes.Figure 3 shows the quantity and proportion of different categories，Figure 4 shows Real and Groundtruth in the Jiliang-3D dataset.

<img width="692" height="266" alt="image" src="https://github.com/user-attachments/assets/daa43699-fad6-4487-b627-16ccca8c7c7d" />

Figure 3 The number and proportion of classes in the Jiliang-3D dataset

<img width="691" height="456" alt="image" src="https://github.com/user-attachments/assets/ddb19b0e-5fdd-4f9c-af6a-cae88b446a5b" />

Figure 4 Real and Groundtruth in the Jiliang-3D dataset

# Reference
Hu, Qingyong, et al. Towards semantic segmentation of urban-scale 3D point clouds: A dataset, benchmarks and challenges.
Liu C, Zeng D, Akbar A, et al. Context-aware network for semantic segmentation toward large-scale point clouds in urban environments.
