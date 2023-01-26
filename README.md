# EyeDiseaseRecognizer

# Motive/ Goal

Motive and is making a Ai based Eye Diagonestic machine that can detect any eye problem of a person.

# Description

  ***Data Collection***<br/>
  Data collected from: https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification </br>
  This dataset contains huge data, almost 4500+ images found.
  
  ***Data Modification***<br/>
  This dataset contains qualityfull images. As all images has same color but different in shade so i convert images into `GrayScale`. That process reduce trainning time
  helpful for internal calculation, increase `Accuracy`.
  
  Using `RGB` images I've got 81% accuracy.<br>
  But for `GrayScale` images `Accuracy` increased to 86%.
  
  ***FrameWork***<br/>
  For this project I use `Google Colab`, `FastAi`, `Pytorch` libraries. These are really helpful to implement code.
  
  ***Model selection***<br/>
  In this project I've experiment with different models. Finally, FastAi provides `xresnet34deeper` model, that gave me better result than another model.
  I've tried `Resnet34`, `Resnet50`, `vgg16` and lastly `xresnet34_deeper`.
  
  ***Train and validation***</br>
  I tried 4 times to train models and I've got some findings.<br>
  |   Model       |     Accuracy|
  |---------------|-------------|
  | Resnet34      |      80%    |
  | Resnet50      |      81%    |
  | vgg16         |      79%    |
  | xresnet34_deeper with rgb image| 84%|
  |xresnet34_deeper with GrayScale image |86%|
  
  ## Deployment
  
  I deployed my project on `HuggingFace` website. Link is : https://huggingface.co/spaces/Rimi98/EyeDiseaseClassifier
  
  ## Integration
  
  You can use my project from this website: https://aklimarimi.github.io/website/
  
# Output


# Conclusion
