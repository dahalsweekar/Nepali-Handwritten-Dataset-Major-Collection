#  NHD: A Dataset for Nepali Handwriting Detection

# Abstract: 

In this paper, we present the Nepali Handwriting Dataset (NHD), which is a collection of camera-captured images of Nepali handwritten text from various regions in Nepal. The dataset aims to provide a benchmark for researchers to explore new techniques in handwriting detection and recognition. We also present benchmark results for text localization and recognition using well-established deep-learning frameworks. The dataset and benchmark results are available in this repository. 

# Introduction:  

While there have been many datasets for English handwriting recognition, there is a lack of datasets for other languages, including Nepali. Nepali is the official language of Nepal and is also spoken in some parts of India and Bhutan. Like many other languages, Nepali handwriting can vary significantly in style and layout. Detecting and recognizing sequences of Nepali texts in images still poses a significant challenge despite the power of modern learning algorithms. Hence, research on Devanagari script detection and recognition can be found [1], [2] but there are very few researches on Nepali handwriting detection [3], [4].  

Handwriting recognition from images has been a challenging task in the field of document analysis. While the MNIST dataset was widely known for containing grayscale images of handwritten digits, it is no longer a challenging task with the development of deep learning algorithms [5]. However, detecting and recognizing sequences of handwritten texts in images still poses significant challenges due to the variation in writing styles and layouts. Researchers have used recurrent neural networks and connectionist temporal classification loss to solve word recognition and line recognition problems [6], [7], [8]. However, recognition of a full page of handwriting without explicit segmentation still poses a challenge. 

In Nepal, there has been a lack of datasets for Nepali handwriting, making it difficult for researchers to investigate new techniques in this area. Therefore, we created the Nepali Handwriting Dataset (NHD) consisting of camera-captured images of Nepali handwritten text from various regions in Nepal. The dataset includes 1000 images with 250,000 characters, 50,000 texts, and 10,000 lines. We hope that the NHD will provide a useful benchmark for researchers to explore new techniques in handwriting detection and recognition. 

Our goal is to provide a benchmark dataset for researchers to investigate new localization and text recognition techniques for Nepali handwriting. We also provide baseline models for text localization and recognition using well-studied frameworks. Our contributions include the NHD dataset and benchmark results, which can be used to develop more accurate and efficient handwriting recognition systems for Nepali. The NHD dataset and benchmark results are available [here.](https://www.kaggle.com/datasets/sweekardahal/nepali-handwritten-images-for-text-detection)

# Data Collection: 

The role of data collection and preprocessing in the research on handwritten text detection cannot be overstated. It is a crucial aspect that plays a significant role in obtaining a comprehensive and diverse dataset. To this end, the researchers personally collected 1,000 mobile phone-captured data samples from various sources, including schools, government offices, universities, and student councils. 

The dataset was carefully curated to encompass three distinct categories based on age groups, namely kids, youth, and adults, with 599, 152, and 249 samples, respectively. Each of the 1000 pages was meticulously annotated by the researchers to ensure accurate labeling and create a reliable dataset. The data collection process focused on capturing a wide range of handwriting styles and variations prevalent among different age groups and settings.  

The collected dataset served as a valuable resource for training and evaluating the handwritten text detection models in the research. It provided a rich and diverse set of data that enabled the researchers to develop robust models capable of accurately detecting handwritten text across different age groups and settings.  

Hence, the researchers' efforts in data collection and preprocessing were instrumental in the success of the research on handwritten text detection. The meticulous approach taken in collecting and annotating the dataset ensured that the models developed were reliable and accurate. The dataset serves as a valuable resource for future research in this field. 

# Below are the results of text detection after training in the DBNet.
Image 1             |  Image 2    |  Image 3
:-------------------------:|:------------------------|:--------------------
![received_610481524530847](https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection/assets/99968233/e258c37d-7151-4262-840d-85439139197a)|![received_532563362328992](https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection/assets/99968233/142e72e9-5e09-4609-828a-6722d66518be)|![received_966052277974189](https://github.com/dahalsweekar/Nepali-Handwritten-Dataset-Major-Collection/assets/99968233/1a5912e0-ea20-4ce8-a2ec-dc974748d504)

# Results
| Precision | Recall | HMean |
| ------------- | ------------- | ------------- |
|91.79|90.69|91.24|

# If you find this repository useful, please cite our work
```
@misc{Dahal_Nepali_Handwritten_Collection_2023,
author = {Dahal, Sweekar  and Gautam, Saramsh},
month = Jul,
title = {{Nepali Handwritten Collection}},
url = {https://www.kaggle.com/datasets/sweekardahal/nepali-handwritten-images-for-text-detection},
year = {2023}
}
```
# Appreciation
Our work was carried on by our friend Rajan Ghimire.
You can find its implementation here: https://github.com/R4j4n/Nepali-Text-Detection-DBnet

# Citations

[1] LeCun, Y., Bottou, L., Bengio, Y., Haffner, P.: Gradient-based learning applied to document recognition. Proceedings of the IEEE 86(11), 2278–2324 (1998) 

[2] Graves, A., Liwicki, M., Fernandez, S., Bertolami, R., Bunke, H., Schmidhuber, J.: A novel connectionist system for unconstrained handwriting recognition. IEEE transactions on pattern analysis and machine intelligence 31(5), 855–868 (2008) 

[3] Shi, B., Bai, X., Yao, C.: An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition. IEEE transactions on pattern analysis and machine intelligence 39(11), 2298–2304 (2016) 

[4] Voigtlaender, P., Doetsch, P., Ney, H.: Handwriting recognition with large multidimensional long short-term memory recurrent neural networks. In: 2016 15th International Conference on Frontiers in Handwriting Recognition (ICFHR). pp. 228–233. IEEE (2016) 

[5] K. C. Santosh and C. Nattee, “Template-based nepali handwritten alphanumeric character recognitNepaliThammasat International Journal of Science and Technology (TIJSAT), Thammasat University, Thailand, vol. 12, no. 1, 2007. 

[6] Pant, A. K., Panday, S. P., & Joshi, S. R. (2012). Off-line Nepali handwritten character recognition using Multilayer Perceptron and Radial Basis Function neural networks. 2012 Third Asian Himalayas International Conference on Internet 

[7] P. S. Deshpande, L. Malik, and S. Arora, “Fine classification & recognition of handwritten Devanagari characters with regular expressions & minimum edit distance method,” JCP, vol. 3, no. 5, pp. 11–17, 2008. 

[8] S. Arora, D. Bhattacharjee, M. Nasipuri, D. K. Basu, and M. Kundu, “Multiple classifier combination for off-line handwritten Devanagari character recognition,” Jun. 30, 2010. 
