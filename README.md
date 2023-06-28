### <div align="center"> Unofficial pytorch reimplementation of </div>
# <div align="center"> SER-FIQ: Unsupervised Estimation of Face Image Quality Based on Stochastic Embedding Robustness </div>
### <div align="center"> CVPR 2020 </div>

<div align="center">
  Authors: 
  <br>
  Philipp Terhorst, Jan Niklas Kolf, Naser Damer, Florian Kirchbuchner, Arjan Kuijper
  <br>
  <br>
  <br>
  <a 
    href="https://openaccess.thecvf.com/content_CVPR_2020/papers/Terhorst_SER-FIQ_Unsupervised_Estimation_of_Face_Image_Quality_Based_on_Stochastic_CVPR_2020_paper.pdf">
    <img src="https://github.com/jankolf/assets/blob/main/IDnet/paper-thecvf.com.svg?raw=true" alt="Paper available at TheCVF">
  </a>
  <a 
    href="https://share.jankolf.de/s/F64PNQjsQLpmGLW">
    <img src="https://github.com/jankolf/assets/blob/main/IDnet/data-download.svg?raw=true" alt="Data available to download"> 
  </a>
</div>

### Reimplementation
SER-FIQ is implemented for iResNet architecture, pre-trained iResNet18 and iResNet50 are provided.
The scaling of the SER-FIQ scores is different from the original implementation and needs to be adapted to the dataset/model.

### Run
To run the example code, 
1. download the [model checkpoints](https://share.jankolf.de/s/F64PNQjsQLpmGLW)
2. create a folder checkpoints and copy the file into it
3. Execure the example code with
   ```
   python main.py
   ```
### Dependencies
Tested with pytorch 2.0, torchvision.

### License
This project is licensed under the terms of the Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.
