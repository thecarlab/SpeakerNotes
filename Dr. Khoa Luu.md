# Robust Vision Learning Approaches to Perception, Multi-Object Tracking and Human Behavior Understanding in Open-World Environments
### Dr. Khoa Luu: Assistant Professor and the Director of the Computer Vision and Image Understanding (CVIU) Lab in the Department of Electrical Engineering and Computer Science (EECS) at the University of Arkansas (UA)

## Abstract
The self-operation of autonomous vehicles (AV) and unmanned aerial vehicles(UAV) in open-world environments heavily relies on the robustness of the visual perception model. The perception model needs to understand the surrounding scene, track the target objects, and analyze the human behaviors of the surrounding objects. Although applications of AV in on-road or urban scenarios where the objects and
environments have been well studied for many years, their deployment in in-the-wild environments still needs to be improved. In particular, the operation of AV in the open-world environment differs from the one in urban environments where the AV may encounter new types of objects or new unseen scenarios.

In this presentation, we will present our recent studies in robust and fair vision-based perception approaches to AV and UAV. To improve self-operation capability in open-world environments, we will introduce our recent work in vision learning approaches to fairness continual learning, and cross-domain adaptation. In addition, to advance the tracking ability of the perception model, our recent work in prompted-based multi-camera multi-object tracking via large-language models will be presented. Then, to further enlarge the operation of the perception model in analyzing the surrounding activities, we will introduce novel self-supervised learning approaches to social group activity recognition.

## Notes
* Classical vision model: input -> encoder > feature > decoder > output
* Autonomous perception, requires large-scale labeled data, produce biased predictions, cannot handle novel class, limits the open-world deployment
* we have respectively, unsupervised domain adaptation, fairness domain adaptation learning, fairness continual learning
* core technologies for AV: lane detection, lane segmentation, object detection, free space...
* precision machine perception -> robust representation -> multi-modality learning, visual input/audio input -> efficient temporal learning
* Unsupervised domain adaptation: input (source domain simulation) -> supervised learning -> prediction -> transfer to target domain (real world).
* entropy minimization, pixel independence, ignore global structures old CVPR paper
* UDS: unaligned domain scores -> measures the efficiency of the learned model in an unsupervised manner
* fairness domain adaptation learning: FREDOM: class relevant fairness in semantic segmentation
* fairness continual learning: NIPS2023: when the model sees unclassified items, group them
* reconstructing input image given the feature layer
* multi-modality learning
* audio-visual transformer approach
* efficient temporal learning: DirectFormer: CVPR 2022
* cross-view robust representation: car view + drone view
* Micron-BERT: CVPR 2023

