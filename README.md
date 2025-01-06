![image](https://github.com/chienthan2vn/Age-Gender-Prediction/blob/main/UTKFaceDemo.png)

### __Project__ 
- This is an project which uses __multi model__ architectured model on image data  as  __hybrid model__.The project uses the  [__UTKFace Dataset__](https://www.kaggle.com/datasets/jangedoo/utkface-new) to __predict the age and gender__ of any person from image.
- The __goal__ is build a deep learning model that accurately __predicting the age and gender__ of any person from image..
- The performance of the model is evaluated using several __metrics__ loss and accuracy metrics.

**Project Workflow**

1. **Data Exploration:** We delve into the UTKFace dataset, understanding its nuances, and extracting vital information for our models.

2. **Model Design:** Together, we design two CNN models - one from scratch and another by fine-tuning a pre-trained architecture.

3. **Training and Optimization:** Our training process involves careful parameter tuning and optimization, ensuring our models capture intricate patterns and nuances.

4. **Results and Analysis:** We present our findings, discussing the performance of both models, their strengths, and areas of improvement.

* ## Datasets
From the origin of the DATA  - from the University of Tennesse and Knoxville
| [In-the-wild Faces](https://drive.google.com/open?id=0BxYys69jI14kSVdWWllDMWhnN2c) | [Aligned&Cropped Faces](https://drive.google.com/drive/folders/0BxYys69jI14kU0I1YUQyY1ZDRUE?usp=sharing) | [Landmarks (68 points)](https://drive.google.com/open?id=0BxYys69jI14kS1lmbW1jbkFHaW8) |
| :---: | :---: | :---: |
| ![In-the-wild Faces](icon/zip-file-128.png) | ![Aligned&Cropped Faces](icon/zip-file-128.png) | ![Landmarks (68 points)](icon/text-file-icone-9457-128.png) 
| [ZIP File (1.3GB)](https://drive.google.com/open?id=0BxYys69jI14kSVdWWllDMWhnN2c) | [ZIP File (107MB)](https://drive.google.com/drive/folders/0BxYys69jI14kU0I1YUQyY1ZDRUE?usp=sharing) |  [TXT File (12MB)](https://drive.google.com/open?id=0BxYys69jI14kS1lmbW1jbkFHaW8) |


From the external public access Kaggle 
https://www.kaggle.com/datasets/jangedoo/utkface-new
## License Claim

* The UTKFace dataset is avaiable for non-commercial research purposes only.
* The aligned and cropped images, as well as landmarks, are obtained by [Dlib](http://dlib.net/).
* Please note that all the images are collected from the Internet which are not property of [AICIP](http://aicip.eecs.utk.edu/wiki/Main_Page). AICIP is not responsible for the content nor the meaning of these images.
* The copyright belongs to the original owners. If any of the images belongs to you, please let us know and we will remove it from our dataset immediately. 
* The ground truth of age, gender and race are estimated through the [DEX](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/)  algorithm and double checked by a human annotator. If you find anything inaccurate, please let us know.
