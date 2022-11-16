# Detection-of-Covid-19-from-Chest-Radiographs
This research work serves the purpose of  detecting covid-19 from chest x-ray images. During the pandemic, we have conducted this research realizing the gravity of it during those time.

## Abstract
<p align = "justify">
Despite the combined effort, the COVID-19 pandemic continues with a devastating effect on the healthcare
system and the well-being of the world population. With a lack
of RT-PCR testing facilities, one of the screening approaches
has been the use of is chest radiography. In this paper, we
propose an automatic chest x-ray image classification model
that utilizes the pre-trained CNN architecture (DenseNet121,
MobileNetV2) as a feature extractor, and wavelet transformation
of the pre-processed images using the CLAHE algorithm and
SOBEL edge detection. Our model can detect COVID-19 from
x-ray images with high accuracy, sensitivity, specificity, and
precision. The result analysis of different architectures and
a comparison study of pre-processing techniques (Histogram
Equalization and Edge Detection) are thoroughly examined. In
this experiment, the Support Vector Machine (SVM) classifier
fitted most accurately (accuracy 97.73%, sensitivity 97.84%, F1-
score 97.73%, specificity 97.73%, and precision 98.79%) with a
wavelet and MobileNetV2 feature sets to identify COVID-19. The
memory consumption is also examined to make the model more
feasible for telemedicine and mobile healthcare application. </p>

## Proposed Method:Schematic Diagram
<img src ="https://github.com/PrasunDatta/Detection-of-Covid-19-from-Chest-Radiographs/blob/main/ProposedMethodSchematic.PNG" align = "center" />

## Heatmaps
 <img src ="https://github.com/PrasunDatta/Detection-of-Covid-19-from-Chest-Radiographs/blob/main/Heatmaps/Heatmaps.PNG" align = "center" />
