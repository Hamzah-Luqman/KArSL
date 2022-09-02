# KArSL
KArSL (**K**FUPM **Ar**abic **S**ign **L**anguage) is an Arabic sign language (ArSL) database collected using Microsoft Kinect V2. The database consists of **502 sign words** constitute the sign words of eleven chapters of ArSL dictionary (Letters, Numbers, Health, Common verbs, Family, Characteristics, Directions and places, Social relationships, In house, Religion, and Jobs and professions). Each sign of the database is performed by three professional signers. The signers involved in this database are all male and their age is between 30 and 40 years. Each signer repeated **each sign 50 times** which resulted in a total of **75,300 samples** of the whole database **(502 x 3 x 50)** as shown in the table below. 

<!-- <div>
<img src="[attachment:https://user-images.githubusercontent.com/106232682/170251559-6ffe7c7f-6d00-4874-b7ec-4967ee7fa85e.png]" width="500"/>
</div>
 -->

<!-- ![image width="500" align="center"](https://user-images.githubusercontent.com/106232682/170251559-6ffe7c7f-6d00-4874-b7ec-4967ee7fa85e.png) -->
<!-- ![image width="500" align="center"](https://user-images.githubusercontent.com/106232682/170251559-6ffe7c7f-6d00-4874-b7ec-4967ee7fa85e.png) -->

<p align="center">
<img align="center" width="50%" src="https://user-images.githubusercontent.com/106232682/170251559-6ffe7c7f-6d00-4874-b7ec-4967ee7fa85e.png" >
</p>

KArSL is the first database for ArSL with such a large number of samples. Table 2 shows a comparison between our database and the top five largest databases used in the literature.

<!-- ![image](https://user-images.githubusercontent.com/106232682/170276408-194b0473-c4e0-4787-86ce-668f36230bbf.png)
 -->
 
 <p align="center">
 <img align="center" width="60%" src="https://user-images.githubusercontent.com/106232682/170276408-194b0473-c4e0-4787-86ce-668f36230bbf.png">
 </p>
 
## Setup and recording software
All signs of KArSL are recorded in an unconstrained environment. We didn’t use dedicated lights in the recording room as the room
lights were adequate and no shadow is shown in the records. We used fixed background (green) to
facilitate background removal for researchers who prefer using color video recording. In addition,
the signers were not restricted to wear specific clothes or remove eye glasses or watches. Each
sign is recorded by each signer in two sessions where the signer wearing different clothes in each
session. To add more variety to the database, some signs, alphabets, are performed alternately
between the left and right hands of the signer.

<!-- ![image](https://user-images.githubusercontent.com/106232682/170277039-0a399b3f-5dc0-403b-bdb6-13978616157d.png) -->
<p align="center">
<img align="center" width="60%" src="https://user-images.githubusercontent.com/106232682/170277039-0a399b3f-5dc0-403b-bdb6-13978616157d.png">
</p>

## Samples of the data

All signs are available in three modalities: (a) RGB, (b) depth, and (c) skeleton joint points as shown the followin figure.

<p align="center">
<img align="center" width="60%" src="https://user-images.githubusercontent.com/106232682/170286084-0c8f2e69-6962-45de-b3b7-ef17bcbf7a55.png">
</p>

## Citing
If you use KArSL dataset, we kindly ask you to cite [**_KArSL: Arabic Sign Language Database_**](https://dl.acm.org/doi/10.1145/3423420#:~:text=Signs%20in%20KArSL%20database%20are,language%20recognition%20using%20this%20database) paper:

```
@article{sidig2021karsl, 
  title={KArSL: Arabic Sign Language Database}, 
  author={Sidig, Ala Addin I and Luqman, Hamzah and Mahmoud, Sabri and Mohandes, Mohamed}, 
  journal={ACM Transactions on Asian and Low-Resource Language Information Processing (TALLIP)},  
  volume={20}, 
  number={1}, 
  pages={1--19}, 
  year={2021}, 
  publisher={ACM New York, NY, USA} 
}
```


## Dataset download 
There are three subsets of the dataset:
### KArSL-100
This dataset consists of 100 dynamic signs of KArSL dataset (from signID 0071 to 0170). Please follow the links below to download it:  
- [**RGB resized images (256x256x3)**](https://kfupmedusa-my.sharepoint.com/:f:/g/personal/hluqman_kfupm_edu_sa/Eli1BoG0CARBpF3HAeue5hEBYZWC-LYSR_dD8rkP8VJwyQ?e=nHkR6A)
- Depth images  
- Skeleton  

To download the raw video files of this data, please follow the links below:
- RGB video files [Signer 01, Signer 02, Signer 03]
- Depth data [Signer 01, Signer 02, Signer 03]


### KArSL-190
This dataset consists of 190 static and dynamic signs of KArSL dataset (from signID 0001 to 0190). Please follow the links below to download it:  
- RGB resized images (256x256x3)
- Depth images
- Skeleton

To download the raw video files of this data, please follow the links below:
- RGB video files
- Depth data

### KArSL-502
This dataset consists of 502 static and dynamic signs (whole KArSL dataset signs) (from signID 0001 to 0502). Please follow the links below to download it:  
- RGB resized images (256x256x3)
- Depth images
- Skeleton

To download the raw video files of this data, please follow the links below:
- RGB video files
- Depth data
