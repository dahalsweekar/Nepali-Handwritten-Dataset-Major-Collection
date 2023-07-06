#  NHD: A Dataset for Nepali Handwriting Detection

# Abstract: 

In this paper, we present the Nepali Handwriting Dataset (NHD), which is a collection of camera-captured images of Nepali handwritten text from various regions in Nepal. The dataset aims to provide a benchmark for researchers to explore new techniques in handwriting detection and recognition. We also present benchmark results for text localization and recognition using well-established deep learning frameworks. The dataset and benchmark results are available in this repository. 

# Introduction:  

While there have been many datasets for English handwriting recognition, there is a lack of datasets for other languages, including Nepali. Nepali is the official language of Nepal and is also spoken in some parts of India and Bhutan. Like many other languages, Nepali handwriting can vary greatly in style and layout. Detecting and recognizing sequences of Nepali texts in images still pose a significant challenge despite the power of modern learning algorithms. Hence, researches on Devanagari script detection and recognition can be found [7], [8] but there are very few researches on Nepali handwriting detection [5], [6].  

Handwriting recognition from images has been a challenging task in the field of document analysis. While the MNIST dataset was widely known for containing grayscale images of handwritten digits, it is no longer a challenging task with the development of deep learning algorithms [1]. However, detecting and recognizing sequences of handwritten texts in images still pose significant challenges due to the variation in writing styles and layouts. Researchers have used recurrent neural networks and connectionist temporal classification loss to solve word recognition and line recognition problems [2], [3], [4]. However, recognition of a full page of handwriting without explicit segmentation still poses a challenge. 

In the context of Nepal, there has been a lack of datasets for Nepali handwriting, making it difficult for researchers to investigate new techniques in this area. Therefore, we created the Nepali Handwriting Dataset (NHD) consisting of camera-captured images of Nepali handwritten text from various regions in Nepal. The dataset includes 1000 images with 250,000 characters, 50,000 texts, and 10,000 lines. We hope that the NHD will provide a useful benchmark for researchers to explore new techniques in handwriting detection and recognition. 

Our goal is to provide a benchmark dataset for researchers to investigate new localisation and text recognition techniques for Nepali handwriting. We also provide baseline models for text localisation and recognition using well-studied frameworks. Our contributions include the NHD dataset and benchmark results, which can be used to develop more accurate and efficient handwriting recognition systems for Nepali. The NHD dataset and benchmark results are available at https://www.dropbox.com/s/c40fcdo4pul0dks/Dataset.zip?dl=0. 

# Data Collection: 

The role of data collection and preprocessing in the research on handwritten text detection cannot be overstated. It is a crucial aspect that plays a significant role in obtaining a comprehensive and diverse dataset. To this end, the researchers personally collected 1000 mobile phone-captured data samples from various sources, including schools, government offices, universities, and student councils. 

The dataset was carefully curated to encompass three distinct categories based on age groups, namely kids, youth, and adults, with 599, 152, and 249 samples, respectively. Each of the 1000 pages was meticulously annotated by the researchers to ensure accurate labeling and create a reliable dataset. The data collection process focused on capturing a wide range of handwriting styles and variations prevalent among different age groups and settings.  

The collected dataset served as a valuable resource for training and evaluating the handwritten text detection models in the research. It provided a rich and diverse set of data that enabled the researchers to develop robust models capable of accurately detecting handwritten text across different age groups and settings.  

Hence, the researchers' efforts in data collection and preprocessing were instrumental in the success of the research on handwritten text detection. The meticulous approach taken in collecting and annotating the dataset ensured that the models developed were reliable and accurate. The dataset serves as a valuable resource for future research in this field. 

# If you find this repository useful, please cite our work
```
@misc{Dahal_Nepali_Handwritten_Collection_2023,
author = {Dahal, Sweekar  and Gautam, Saramsh},
month = jul,
title = {{Nepali Handwritten Collection}},
url = {https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection},
year = {2023}
}
```

# Below are the results of text detection after training with the VGG-16 model.

![demo_result_1](https://user-images.githubusercontent.com/99968233/231123776-04298aeb-e8f1-427a-a8d3-f2d1ab7c5a69.jpg)
![demo_result_2](https://user-images.githubusercontent.com/99968233/231123798-29bf6b0a-0287-4a4a-8694-ecb864c5fdef.jpg)
![demo_result_3](https://user-images.githubusercontent.com/99968233/231123809-b8635766-8ef7-4ffd-8324-38fa37ea386a.jpg)
![demo_result_4](https://user-images.githubusercontent.com/99968233/231123819-aaecfb48-881b-48b2-aee7-adb9d09357cd.jpg)
![demo_result_5](https://user-images.githubusercontent.com/99968233/231123828-cd893fc9-7647-489e-a4b6-b23d30d8570e.jpg)
![demo_result_6](https://user-images.githubusercontent.com/99968233/231123840-261d664e-6423-461f-9fb6-e22ae898dc51.jpg)
![demo_result_7](https://user-images.githubusercontent.com/99968233/231123850-4ac63700-7268-4360-800e-3b459b17de1f.jpg)
![demo_result_8](https://user-images.githubusercontent.com/99968233/231123862-3a98569a-be08-4d64-b241-820e38a425f8.jpg)
![demo_result_9](https://user-images.githubusercontent.com/99968233/231123879-7b41ce99-9b90-428a-9e70-e244ebcfdcb3.jpg)
![demo_result_10](https://user-images.githubusercontent.com/99968233/231123889-70c46e2c-b0fb-4a5d-b290-4a888ec4068a.jpg)
![demo_result_11](https://user-images.githubusercontent.com/99968233/231123895-d6a9f7dc-4771-415d-9c06-003c5e99e58b.jpg)
![demo_result_12](https://user-images.githubusercontent.com/99968233/231123912-3e298714-03a7-4c23-aee7-b50c97d23716.jpg)
![demo_result_13](https://user-images.githubusercontent.com/99968233/231123930-1b6f8321-8fe6-41d7-9def-e2946e11bcfa.jpg)
![demo_result_14](https://user-images.githubusercontent.com/99968233/231123939-a06a50a5-552a-438c-af79-1c5f37b31084.jpg)
![demo_result_15](https://user-images.githubusercontent.com/99968233/231123953-5c85eaba-e2e2-455b-92a7-91bc2bea8600.jpg)
![demo_result_16](https://user-images.githubusercontent.com/99968233/231123963-1ec00224-2c41-4dff-8963-1ba811521d1b.jpg)
![demo_result_17](https://user-images.githubusercontent.com/99968233/231123972-533359ae-b107-4e90-82bd-91cfefa6eeea.jpg)
![demo_result_18](https://user-images.githubusercontent.com/99968233/231123979-3e428881-c995-4b09-b2b8-ae635f0666ad.jpg)
![demo_result_19](https://user-images.githubusercontent.com/99968233/231123985-f1f19715-1e01-4cea-93d6-6368f9381b99.jpg)
![demo_result_20](https://user-images.githubusercontent.com/99968233/231123991-2bc4029f-e5db-4456-98f7-3f2e197ba5d4.jpg)
![demo_result_21](https://user-images.githubusercontent.com/99968233/231124000-de022d6a-ebf5-47e9-9fd8-ad0841110bed.jpg)
![demo_result_22](https://user-images.githubusercontent.com/99968233/231124006-3586b368-eb39-4c38-b71c-04f0276905d9.jpg)
![demo_result_23](https://user-images.githubusercontent.com/99968233/231124013-ce220f07-6dd7-4878-982e-bd4895251f26.jpg)
![demo_result_24](https://user-images.githubusercontent.com/99968233/231124021-3476244b-200c-4174-9370-2b4efd60d2d8.jpg)
![demo_result_25](https://user-images.githubusercontent.com/99968233/231124035-a3007506-31d1-466f-a992-77492aca00a6.jpg)
![demo_result_26](https://user-images.githubusercontent.com/99968233/231124040-08b022fa-d1ca-4360-9844-20f7de8c9ecd.jpg)
![demo_result_27](https://user-images.githubusercontent.com/99968233/231124047-f2ae774f-8ee2-429c-9350-7af1fffb7c0d.jpg)
![demo_result_28](https://user-images.githubusercontent.com/99968233/231124053-88056b85-4f17-4724-845d-392e108550c6.jpg)
![demo_result_29](https://user-images.githubusercontent.com/99968233/231124063-f6f960e1-a5cd-421e-9afa-bb734292c6c8.jpg)
![demo_result_30](https://user-images.githubusercontent.com/99968233/231124068-1cbdb31f-84e8-4513-b1d0-e0626ee25d00.jpg)
![demo_result_31](https://user-images.githubusercontent.com/99968233/231124076-539dd4ba-9329-4c47-9668-e851346c4a3f.jpg)
![demo_result_32](https://user-images.githubusercontent.com/99968233/231124081-a2e3ac04-5605-49e5-abe9-37c45fd72e0b.jpg)
![demo_result_33](https://user-images.githubusercontent.com/99968233/231124091-9007dfa9-2590-4d0f-8ebe-83f8639888ef.jpg)
![demo_result_34](https://user-images.githubusercontent.com/99968233/231124102-cd708900-5c27-4a7b-bf67-859a16b75d6a.jpg)
![demo_result_35](https://user-images.githubusercontent.com/99968233/231124107-c059036a-1e0d-42c2-b7a9-00e825e18e5f.jpg)
![demo_result_36](https://user-images.githubusercontent.com/99968233/231124114-216d490b-4fd9-40b9-82b3-56d590903703.jpg)
![demo_result_37](https://user-images.githubusercontent.com/99968233/231124124-d5341f5d-5475-4d8e-ac93-ee08702a6f10.jpg)
![demo_result_38](https://user-images.githubusercontent.com/99968233/231124132-13cc7c18-8b56-461b-b759-8a7704f32744.jpg)
![demo_result_39](https://user-images.githubusercontent.com/99968233/231124139-b6d0bcb1-cb17-4099-afba-f023015ca3c6.jpg)
![demo_result_40](https://user-images.githubusercontent.com/99968233/231124144-e5ed3f4e-0094-4a0b-b6d9-28d5399152e6.jpg)
![demo_result_41](https://user-images.githubusercontent.com/99968233/231124152-bcb04a38-9494-4a27-89bc-801b44ad97ad.jpg)
![demo_result_42](https://user-images.githubusercontent.com/99968233/231124165-4a251b8d-f6e0-4078-a79f-5184d2791d90.jpg)
![demo_result_43](https://user-images.githubusercontent.com/99968233/231124175-d2ead800-45c2-4fd9-b8db-6bc67e73d3c0.jpg)
![demo_result_44](https://user-images.githubusercontent.com/99968233/231124186-a206e888-158a-4a6f-91a9-289024b3cdd9.jpg)
![demo_result_45](https://user-images.githubusercontent.com/99968233/231124193-89cd24fd-d5de-424e-96ac-823f3e112810.jpg)
![demo_result_46](https://user-images.githubusercontent.com/99968233/231124199-90e44911-4fec-44c1-9463-cadaaefe04c5.jpg)
![demo_result_47](https://user-images.githubusercontent.com/99968233/231124213-41565754-74cd-4169-9b6b-5b238ddae4d0.jpg)
![demo_result_48](https://user-images.githubusercontent.com/99968233/231124223-b30b49c1-b046-49f7-afe1-039c6856b093.jpg)
![demo_result_49](https://user-images.githubusercontent.com/99968233/231124230-077cbb51-88d4-4863-9168-0c2c2097bc96.jpg)
![demo_result_50](https://user-images.githubusercontent.com/99968233/231124241-61df4034-f7dc-4cf8-98d3-242360f51dc5.jpg)
![demo_result_51](https://user-images.githubusercontent.com/99968233/231124247-42676457-eace-4c15-ba32-2e23ec23f95a.jpg)
![demo_result_52](https://user-images.githubusercontent.com/99968233/231124251-2e71950c-c179-4d22-ab16-51fc528cac96.jpg)
![demo_result_53](https://user-images.githubusercontent.com/99968233/231124259-3b86af6d-e594-45d6-aa3f-ee9ac213bb90.jpg)
![demo_result_54](https://user-images.githubusercontent.com/99968233/231124266-ce5a09d4-a900-4b35-ba9e-840e2fd6e1d7.jpg)
![demo_result_55](https://user-images.githubusercontent.com/99968233/231124271-852d9c57-9eb4-422a-b860-cfb0bff01b25.jpg)
![demo_result_56](https://user-images.githubusercontent.com/99968233/231124279-97a62f1a-f995-4b67-b9c3-6ad99491a774.jpg)
![demo_result_57](https://user-images.githubusercontent.com/99968233/231124287-984f0377-aa94-46cc-9eff-f9eb96cf8cb3.jpg)
![demo_result_58](https://user-images.githubusercontent.com/99968233/231124292-33b98513-09d4-4f02-a78f-932a29971940.jpg)
![demo_result_59](https://user-images.githubusercontent.com/99968233/231124300-7a4c45d8-bca7-4957-b722-49b23369a4e6.jpg)
![demo_result_60](https://user-images.githubusercontent.com/99968233/231124307-30c4ada0-a5d5-4d32-b479-9e02f853c28d.jpg)
![demo_result_61](https://user-images.githubusercontent.com/99968233/231124318-f0b607f3-55ef-49ff-bc51-8af90ebf6245.jpg)
![demo_result_62](https://user-images.githubusercontent.com/99968233/231124326-de6eef63-df41-4c67-b3d6-97c2acb94053.jpg)
![demo_result_63](https://user-images.githubusercontent.com/99968233/231124339-c70a0949-e3e1-43a3-9702-57932a002600.jpg)
![demo_result_64](https://user-images.githubusercontent.com/99968233/231124351-05f10c47-7312-44ce-ab5e-5bec73c2f5e2.jpg)
![demo_result_65](https://user-images.githubusercontent.com/99968233/231124358-968aa388-25d4-4d8d-a410-c78c89bae391.jpg)
![demo_result_66](https://user-images.githubusercontent.com/99968233/231124366-51e39d8e-dea1-40a8-beba-1bc1b39d9527.jpg)
![demo_result_67](https://user-images.githubusercontent.com/99968233/231124374-f3a9c3f0-0788-4bb6-8ad4-313cc37daf25.jpg)
![demo_result_68](https://user-images.githubusercontent.com/99968233/231124379-e827990d-a24b-41a3-b4bd-a4a7ee68d5d4.jpg)
![demo_result_69](https://user-images.githubusercontent.com/99968233/231124383-1b8bd9da-7d99-4d31-abee-a3e8e8fe7caa.jpg)
![demo_result_70](https://user-images.githubusercontent.com/99968233/231124390-e56cef32-fd7b-4638-b4a6-e5045776fe45.jpg)

[1] LeCun, Y., Bottou, L., Bengio, Y., Haffner, P.: Gradient-based learning applied to document recognition. Proceedings of the IEEE 86(11), 2278–2324 (1998) 

[2] Graves, A., Liwicki, M., Fern´andez, S., Bertolami, R., Bunke, H., Schmidhuber, J.: A novel connectionist system for unconstrained handwriting recognition. IEEE transactions on pattern analysis and machine intelligence 31(5), 855–868 (2008) 

[3] Shi, B., Bai, X., Yao, C.: An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition. IEEE transactions on pattern analysis and machine intelligence 39(11), 2298–2304 (2016) 

[4] Voigtlaender, P., Doetsch, P., Ney, H.: Handwriting recognition with large multidimensional long short-term memory recurrent neural networks. In: 2016 15th International Conference on Frontiers in Handwriting Recognition (ICFHR). pp. 228–233. IEEE (2016) 

[5] K. C. Santosh and C. Nattee, “Template-based nepali handwritten alphanumeric character recognition,” Thammasat International Journal of Science and Technology (TIJSAT), Thammasat University, Thailand, vol. 12, no. 1, 2007. 

[6] Pant, A. K., Panday, S. P., & Joshi, S. R. (2012). Off-line Nepali handwritten character recognition using Multilayer Perceptron and Radial Basis Function neural networks. 2012 Third Asian Himalayas International Conference on Internet 

[7] P. S. Deshpande, L. Malik, and S. Arora, “Fine classification & recognition of hand written devnagari characters with regular expressions & minimum edit distance method,” JCP, vol. 3, no. 5, pp. 11–17, 2008. 

[8] S. Arora, D. Bhattacharjee, M. Nasipuri, D. K. Basu, and M. Kundu, “Multiple classifier combination for off-line handwritten devnagari character recognition,” Jun. 30 2010. 
