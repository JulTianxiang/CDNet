# CDNet
CDNet: object detection based on cross-level aggregation and deformable attention for UAV aerial images

# Abstract
Object detection in unmanned aerial vehicle (UAV) imagery is a crucial task. However, the presence of densely populated small objects and significant scale and shape variations among objects in aerial images pose challenges for the detection task. To mitigate these issues, this paper proposes a cross-level deformable feature aggregation network (CDNet). To begin with, a high-resolution characterization enhancement with deep reduction (HCEDR) structure is designed to extract high-resolution small object location detail features while reducing redundant deep interference. Furthermore, a cross-level fusiform feature aggregation (CFFA) structure is proposed to fuse multi-scale cross-level feature information and dense small object spatial detail information. Moreover, to address the challenge of object shape variations caused by varying aerial viewpoints, a deformable attention bottleneck (DAB) module is designed to enhance the model's boundary sensitivity for irregularly shaped objects in aerial scenes. Finally, a new bounding box loss function (Inner-WIoU) is introduced, which, in addition to reducing the harmful gradient contributions from extreme samples, adjusts auxiliary bounding box sizes to achieve better fitting of ground-truth object bounding boxes, thereby improving model performance. To validate the model's superiority, extensive experiments were conducted on the VisDrone2021 and TinyPerson datasets, achieving mAP50 improvements of 10.8% and 3.6%, respectively, compared to baseline methods. Compared to other advanced methods, CDNet achieves superior detection performance. 

# Datasets
The two datasets used in this research can be downloaded from [VisDrone](https://github.com/VisDrone/VisDrone-Dataset), [TinyPerson](https://github.com/ucas-vg/PointTinyBenchmark/tree/TinyBenchmark).
