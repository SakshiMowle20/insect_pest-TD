# insect_pest-TD
Objective: The objective of this assignment is to understand and apply the process of preparing a polygonal dataset for insect segmentation using the Mask-RCNN framework. You will learn how to handle and preprocess datasets with polygonal annotations and prepare them for training a deep learning model for segmentation tasks. Task Requirements:

Background Research: • Explain the need for insect segmentation in paddy fields and its significance in agriculture. • Discuss why polygonal annotations are preferred for segmentation tasks like insect detection. • Briefly describe the Mask-RCNN architecture and its suitability for segmentation tasks. Highlight the key components such as the backbone (e.g., ResNet), ROI pooling, and mask head.

Dataset Preprocessing: Dataset Understanding: Given a dataset of paddy field images annotated with polygonal masks representing different types of insects, explain the key steps in understanding and organizing the dataset. • What are polygonal annotations? • How do these annotations differ from bounding boxes or pixel-wise annotations? • Explain how polygonal annotations are stored (e.g., in COCO format).

Data Augmentation • Data augmentation is essential for enhancing model robustness. Implement various augmentation techniques suitable for insect segmentation, such as: o Random horizontal and vertical flips o Random scaling and rotation o Brightness and contrast adjustments • Ensure that augmentations are applied consistently to both the images and the corresponding masks.

Model Development • Load the pre-processed dataset into the Mask-RCNN model • Write a Python script to prepare the dataset for Mask-RCNN training, making sure to use libraries such as PyTorch, TensorFlow, or Detectron2. • Make sure the annotations (masks and labels) are in the format expected by the Mask-RCNN framework.

Model Evaluation • Research and explain appropriate evaluation metrics for segmentation tasks, such as: o Intersection over Union (IoU) o Mean Average Precision (mAP) o Pixel Accuracy

Conclusion and Future Scope • Summarize the outcomes and evaluate the efficiency of your computer vision solution, particularly in the context of image segmentation. • Outline the obstacles encountered and insights gained throughout the practical analysis. • Mention potential future use cases for the developed paddy field insect image segmentation model.

Additional Resources: • Software for dataset labelling: o cvat Tools (https://app.cvat.ai/auth/login) or any other data labelling tools you can use or you can use free data labelling tool (https://www.makesense.ai/)

o Dataset from this web link (https://www.kaggle.com/datasets/zeeniye/paddy-pests-datas)
