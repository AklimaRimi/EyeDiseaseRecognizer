![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FEyeDiseaseRecognizer%2F&label=views&labelColor=%23697689&countColor=%23f47373)


# EyeDiseaseRecognizer

# Motive/ Goal

Motive and Goal is developing an AI based eye diagnostic machine that can detect eye problems of a person.

# Description

  ***Data Collection***<br/>
  Data collected from: https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification </br>
  This dataset contains huge data, almost 4500+ images found.<br>
  
  ***Data Modification***<br/>
  This dataset contains quality images. Since all the images are the same color but different in shade, I convert the images to `GrayScale`. This process reduces training time, facilitates internal computation, increases `Accuracy`.
  
  Using `RGB` images I've got 81% accuracy.<br>
  But for `GrayScale` images `Accuracy` increased to 86%.<br>
  
  ***FrameWork***<br/>
  For this project I use `Google Colab`, `FastAi`, `Pytorch` libraries. These are really helpful to implement code.
  
  ***Model selection***<br/>
  In this project I've experiment with different models. Finally, FastAi provides `xresnet34deeper` model, that gave me better result than another model.
  I've tried `Resnet34`, `Resnet50`, `vgg16` and lastly `xresnet34_deeper`.<br>
  
  ***Train and validation***</br>
  I tried 4 times to train models and I've got some findings.<br>
  |   Model       |     Accuracy|
  |---------------|-------------|
  | Resnet34      |      80%    |
  | Resnet50      |      81%    |
  | vgg16         |      79%    |
  | xresnet34_deeper with rgb image| 84%|
  |xresnet34_deeper with GrayScale image |86%|
  <br>
  
  
  ***Confusion Matrix*** <br>
  <img src='https://github.com/AklimaRimi/EyeDiseaseRecognizer/blob/main/output/confusion.png' height= '300' width='500'> <br>
  
  
  ***Prediction***<br>
  <img src='https://github.com/AklimaRimi/EyeDiseaseRecognizer/blob/main/output/predicted.png' height='700' width='500'>
  
  
  ## Deployment
  
  I deployed my project on `HuggingFace` website. Link is : https://huggingface.co/spaces/Rimi98/EyeDiseaseClassifier <br>
  
  
  <img src="https://github.com/AklimaRimi/EyeDiseaseRecognizer/blob/main/output/huggingface1.png" width='700' height='400'><br>
  <img src="https://github.com/AklimaRimi/EyeDiseaseRecognizer/blob/main/output/huggingface2.png" width='700' height='400'><br>
  
  
  ## Integration
  
  You can use my project from this website: https://aklimarimi.github.io/website/
  
  <img src = 'https://github.com/AklimaRimi/EyeDiseaseRecognizer/blob/main/output/integration.png' width='800' height='400'>
  

# Conclusion
This project is completed, deployed, integrated.
