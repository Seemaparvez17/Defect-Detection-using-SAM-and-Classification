# Defect-Detection-using-SAM-and-Classification

**Objective :** This project aims to detect defects in Additive manufacturing(3D printing) using a combination of feature extraction with Gabor filters and advanced image segmentation through Segment Anything Model(SAM). This approach enhances defect detection accuracy by addressing challenges like lighting variability, surface texture difference, and the complexity of 3D-printed geometries. Ultimately, the project leverages segmentation maps and neural networks for defect classification, focusing on real-time performance and high accuracy.


**Key Contributions:**
 1. Feature Extraction with Gabor Filters:
       Gabor filters are employed to capture texture and edge details from the images of 3D printing process. This step helps in handling lighting variations and identifying key regons of interest within the images.

2. Segmentation using the Segment Anything Model(SAM):
        SAM uses Gabor filter responses to generate detailed segmentation masks. These masks help isolate components within the printed object capturing their geometries and surface features.

 3. Segmentation Map Creation:
     The Segmentation masks are combined to form comprehensive segmentation maps, which allow for detailed defect analysis,

 4. Intersection Over Union Metric:
    IOU is calculated to evaluate the accuracy of the segmentation by comparing the overlap between the predicted and ground truth masks. Additionally, IOU values close to 1 indicate high accuracy.

 5. Data Augmentation:
    Techniques like rotation, flipping, and adding noise are applied to increase dataset variability without additional data collection, improving the neural network's ability to generalize across defect types.

  6. Neural Network for Classification:
 The final stage involves training a neural network to classify the segmented components and automating defect detection and analysis.
 
     
      
