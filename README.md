# Jiliang-3D: A Large-Scale Urban Outdoor Point Cloud Dataset

# Introduction of the Jiliang-3D datasets
The Jiliang-3D dateset is a large-scale urban outdoor point cloud dateset built by Hexagon Laboratory, China Jiliang University. Based on the analysis of the existing problems in the current large-scale point cloud datasets, our aim is to enrich the large-scale outdoor point cloud datasets and the diversity of static point cloud data


63/5000
It conducts oblique photography on campus through the DJI Mavic 3E drone, and then performs three-dimensional point cloud reconstruction to generate point cloud data. The collection area covers approximately 320,000 square meters.

This data is mainly used to test the performance of semantic segmentation algorithms for large-scale cities' scenes. The data acquisition area scenes are complex and varied, including parking lots, small squares, lawns, dormitory buildings, experimental buildings, and other scenes. The shape of each building is different, there is a certain degree of shielding between the building and the vegetation, and the density of the point cloud varies greatly. To facilitate the training and testing of the network model, the entire model is divided into 10 regions, and the performance of the model is evaluated by selecting different regions with diverse scenarios. The entire point cloud dataset and its division are shown in Figure 1
<img width="782" height="498" alt="image" src="https://github.com/user-attachments/assets/61840711-c40f-424a-be85-0379462fa92f" />
Figure 1 Regional division of Jiliang-3D dataset

# Point cloud semantic labeling
Data labeling is done manually with CloudCompare software. The basic principle of manual semantic annotation is that each category has a precise meaning and can be used for practical value, such as urban planning and asset management.Following the labeling schema of comparable datasets like SensatUrban，ground objects are mainly divided into night categories.


# Distribution of the scene categories

# Reference
