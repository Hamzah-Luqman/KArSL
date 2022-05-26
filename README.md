# KArSL
KArSL (**K**FUPM **Ar**abic **S**ign **L**anguage) is an Arabic sign language (ArSL) database collected using Microsoft Kinect V2. The database consists of **502 sign words** constitute the sign words of eleven chapters of ArSL dictionary (Letters, Numbers, Health, Common verbs, Family, Characteristics, Directions and places, Social relationships, In house, Religion, and Jobs and professions). Each sign of the database is performed by three professional signers. The signers involved in this database are all male and their age is between 30 and 40 years. Each signer repeated **each sign 50 times** which resulted in a total of **75,300 samples** of the whole database **(502 x 3 x 50)** as shown in the table below. 


![image](https://user-images.githubusercontent.com/106232682/170251559-6ffe7c7f-6d00-4874-b7ec-4967ee7fa85e.png)


KArSL is the first database for ArSL with such a large number of samples. Table 2 shows a comparison between our database and the top five largest databases used in the literature.

![image](https://user-images.githubusercontent.com/106232682/170276408-194b0473-c4e0-4787-86ce-668f36230bbf.png)

## Setup and recording software
All signs of KArSL are recorded in an unconstrained environment. We didn’t use dedicated lights in the recording room as the room
lights were adequate and no shadow is shown in the records. We used fixed background (green) to
facilitate background removal for researchers who prefer using color video recording. In addition,
the signers were not restricted to wear specific clothes or remove eye glasses or watches. Each
sign is recorded by each signer in two sessions where the signer wearing different clothes in each
session. To add more variety to the database, some signs, alphabets, are performed alternately
between the left and right hands of the signer.

![image](https://user-images.githubusercontent.com/106232682/170277039-0a399b3f-5dc0-403b-bdb6-13978616157d.png)

## Samples of the data

All signs are available in three modalities: (a) RGB, (b) depth, and (c) skeleton joint points as shown the followin figure.

![image](https://user-images.githubusercontent.com/106232682/170286084-0c8f2e69-6962-45de-b3b7-ef17bcbf7a55.png)

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

We used two sets of the KArSL dataset: KArSL-190 and KArSL-502. KArSL-190 is the pilot version of the KArSL dataset, and it consists of 190 signs that comprise 30 digit signs, 39 letter signs, and 121 word signs. We used this set to evaluate the proposed techniques and compared our work with other studies that used this set. We also evaluated our approach on more signs using KArSL-502, which included all the signs (502 signs) of the KArSL dataset. The results reported for KArSL-502 can also be used to benchmark the KArSL dataset because it is the first study to use the whole KArSL dataset.
