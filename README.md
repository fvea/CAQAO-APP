# Cacao Automated Quality Assessment using Object Detection (CAQAO)

CAQAO is an application used for the quality assessment of cacao beans during the cut test. Users can capture/upload a photo of cacao beans and the application localizes and classifies the quality of the beans in the image using object detection.

## Application Features
- Capture or upload cacao beans image for automated quality assessment based on the [International Standards for the Assessment of Cocoa Quality and Flavour (ISCQF)](https://www.cocoaqualitystandards.org/).
- Classify the cacao bean's degree of fermentation based on color and fissuring and detect defective beans.
- Automatic bean grading based on the [Philippine National Standards for Cacao or cocoa beans- specification and grading](https://bafs.da.gov.ph/bafs_admin/admin_page/pns_file/2022-10-20-Cacao%20or%20cocoa%20beans%20-%20specification%20and%20grading.pdf).
  
## Application Demo
https://github.com/fvea/CAQAO-APP/assets/75005859/6983b3d8-10eb-4fae-8d11-fa7709381219

## Technology Stack
- Kotlin: Android Development
- Kotlin Retrofit and Moshi Libraries
- Flask: Rest API Server
- Ultralytics/Pytorch: YOLOv5 Object Detection Model

## Developers
- Fj Vincent Atabay
- Dea Marielle Cahambing
- Trisha Mae Rafael
- John Michael Tejada
