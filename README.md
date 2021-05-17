# MaskDetectionDatasets
This dataset has been developed for the use in the EE3000 Final Year Project. These images will be used to train a mask detection model which can be run via Google Colab. 

**<img width="343" alt="image" src="https://user-images.githubusercontent.com/77861546/118495444-1a68ae00-b71b-11eb-932a-7169b2c3119a.png">
**

<img width="337" alt="image" src="https://user-images.githubusercontent.com/77861546/118495502-26547000-b71b-11eb-80a2-4f3fa1774257.png">

Images have been collated from 5 publicly avaliable OpenSource datasets and refined to fit the purpose of this project. 

All images belong to their rightful owners and are used purely for educational purposes. 



https://www.kaggle.com/ciplab/real-and-fake-face-detection
https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset
https://github.com/prajnasb/observations/tree/master/experiements/data 
https://github.com/prajnasb/observations/tree/master/experiements/data/with_mask
https://github.com/NVlabs/ffhq-dataset


The model will be trained using the images in the Final-Dataset folder. Training data will be found in the Final_Test folder. Labels are assigned as 'with_mask' and 'without_mask'.

Images have been normlalised and resized prior to classification. Key characteristic of individuals in the images have been manually inspected to undertsand any model biases.

