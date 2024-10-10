# Data augmentation based on generative adversarial networks for endoscopic image classification
This repository is the official code for the paper "Data augmentation based on generative adversarial networks for endoscopic image classification" by Hyuncheol Park*, Inpyo Hong*, Sahadev Poudel, and Chang Choi. [IEEE Access]
(* Equal Contribution)

## Abstract
The incidence of cancer among modern people has recently increased due to various reasons such as eating habits, smoking, and drinking. Therefore, medical image analysis for effective disease diagnosis is considered an extremely important diagnostic tool. In particular, endoscopy is used as a representative screening method for diagnosing diseases of the digestive system. However, it is quite difficult to quickly and thoroughly analyze medical data by relying solely on human vision, such as with endoscopy. Therefore, the purpose of this study was to reduce the fatigue of medical staff through the use of automated disease classification of the digestive system. To automate disease classification, we trained a total of six models, ranging from relatively old deep-learning-based models to recently published approaches. Additionally, to increase the number of medical data, which is generally insufficient, we applied data augmentation using two adversarial generative neural network-based models. We utilized Kvasir version 2 data for the experiment and demonstrated that InceptionNet-V3 showed the best performance improvement when data augmentation based on a Star-GAN was applied experimentally. Furthermore, the approach also exhibited good performance in terms of the F1-Score, which was used to evaluate the safety of the model. Thus, we propose a disease classification automation model centered on safer performance.


![image](https://github.com/user-attachments/assets/8faa2687-3b19-47f1-8176-e581e9a9671d)

## Experimental Results
Top-1 performance comparison.
![image](https://github.com/user-attachments/assets/f56442a7-35b4-4918-b840-7cac4ba9db89)

Top-1 performance comparison with state-of-the-art
![image](https://github.com/user-attachments/assets/7b9afca1-e388-4fa4-8e52-8955faed1875)



## Citation
If you find the project codes useful for your research, please consider citing.
```
@article{park2023data,
  title={Data augmentation based on generative adversarial networks for endoscopic image classification},
  author={Park, Hyun-Cheol and Hong, In-Pyo and Poudel, Sahadev and Choi, Chang},
  journal={IEEE Access},
  volume={11},
  pages={49216--49225},
  year={2023},
  publisher={IEEE}
}
```
