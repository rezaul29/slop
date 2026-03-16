
# Related Work

## Bangladesh Rice Variants Specifics: 

|  No.  | Title                                                                                                      | Link                                                                                                                                            | Main Finding                                                                                                                                                                                                                                                           |
| :---: | :--------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | _PaddyVarietyBD: Classifying paddy variations of Bangladesh with a novel image dataset_                    | [Link](https://www.researchgate.net/publication/390109666_PaddyVarietyBD_Classifying_Paddy_Variations_of_Bangladesh_with_a_Novel_Image_Dataset) | Introduces the **first open dataset** for Bangladeshi **_paddy_ varieties**  14,000 microscopic images of 35 unique types, sourced from **BINA** and **BRRI**. Enables AI-based paddy classification and analysis.                                                     |
| **2** | _An extensive image dataset for deep learning-based classification of rice kernel varieties in Bangladesh_ | [Link](https://www.sciencedirect.com/science/article/pii/S2352340924010710)                                                                     | Dataset of **38 rice varieties** with **19,000 original**  microscopic images, created with **BINA** and **BRRI** to advance rice classification and crop management in Bangladesh.                                                                                    |
| **3** | _Grain by grain: A microscopic image dataset of rice varieties from Bangladeshi rice markets_              | [Link](https://www.sciencedirect.com/science/article/pii/S2352340925007802)                                                                     | Contains **2,010 original (8,010 augmented)** microscopic images of **10 local rice types** (e.g., BR-28, Miniket, Chinigura). Focuses on **milled rice** and effects of **milling and polishing** on quality.                    ![[Pasted image 20251113191417.png]] |
| **4** | _A Visual Dataset for Recognition of Rice Varieties_                                                       | [Link](https://www.sciencedirect.com/science/article/pii/S2352340924004116)                                                                     | Dataset of **20 local varieties** from **Dinajpur and Dhaka** markets, captured via **iPhone 11** including  a total of 4,730 images with a non-uniform distribution.  Useful for developing **mobile-based recognition apps** for farmers and consumers.              |
|       |                                                                                                            |                                                                                                                                                 |                                                                                                                                                                                                                                                                        |
# 1

@article{article,
author = {Tahsin, Md and Ibrahim, Muhammad and Tabassum, Anika and Nuha, Maksura and Arnab, Mehrab and Ferdaus, Md Hasanul and Islam, Mohammad Manzurul and Rashid, Mohammad and Jabid, Taskeed and Ali, Md and Niloy, Nishat},
year = {2025},
month = {03},
pages = {111514},
title = {PaddyVarietyBD: Classifying Paddy Variations of Bangladesh with a Novel Image Dataset.},
volume = {60},
journal = {Data in Brief},
doi = {10.1016/j.dib.2025.111514}
}

# 2

@article{TAHSIN2024111109,
title = {An extensive image dataset for deep learning-based classification of rice kernel varieties in Bangladesh},
journal = {Data in Brief},
volume = {57},
pages = {111109},
year = {2024},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2024.111109},
url = {https://www.sciencedirect.com/science/article/pii/S2352340924010710},
author = {Md Tahsin and Md. Mafiul Hasan Matin and Mashrufa Khandaker and Redita Sultana Reemu and Mehrab Islam Arnab and Mohammad Rifat Ahmmad Rashid and Md Mostofa Kamal Rasel and Mohammad Manzurul Islam and Maheen Islam and Md. Sawkat Ali},
keywords = {Image Classification, Rice Variety Classification, Deep Learning Precision, Rice Image},
abstract = {This article introduces a comprehensive dataset developed in collaboration with the Bangladesh Institute of Nuclear Agriculture (BINA) and the Bangladesh Rice Research Institute (BRRI), featuring high-resolution images of 38 local rice varieties. Captured using advanced microscopic cameras, the dataset comprises 19,000 original images, enhanced through data augmentation techniques to include an additional 57,000 images, totaling 76,000 images. These techniques, which include transformations such as scaling, rotation, and lighting adjustments, enrich the dataset by simulating various environmental conditions, providing a broader perspective on each variety. The diverse array of rice strains such as BD33, BD30, BD39, among others, are meticulously detailed through their unique characteristics—color, size, and utility in agriculture—providing a rich resource for research. This augmented dataset not only enhances the understanding of rice diversity but also supports the development of innovative agricultural practices and breeding programs, offering a critical tool for researchers aiming to analyze and leverage rice genetic diversity effectively.}
}


# 3

@article{TAHSIN2025112058,
title = {Grain by grain: A microscopic image dataset of rice varieties from Bangladeshi rice markets},
journal = {Data in Brief},
volume = {63},
pages = {112058},
year = {2025},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2025.112058},
url = {https://www.sciencedirect.com/science/article/pii/S2352340925007802},
author = {Md Tahsin and Kazi Isat Mahazabin and Maksura Binte {Rabbani Nuha} and Akil Rahman Efad and Mariya Rahman Momo and Nishat Tasnim Niloy and M. Saddam Hossain Khan and Rashedul Amin Tuhin and Mohammad Rifat {Ahmmad Rashid} and Raihan Ul Islam},
keywords = {Rice image, Nutrition, Miniket, Bangladesh rice market, Health, Microscopic image dataset},
abstract = {Although Rice is the staple food of Bangladesh, the practice of cutting and polishing rice to make it look attractive, i.e., thinner, and shinier, leads to serious health concerns. While the motivation behind this process is to increase market value, it leads to the loss of minerals, nutrients, vitamins, and fibers, leaving only carbohydrates, which can result in serious health concerns. This article presents an extensive dataset of images of rice collected from the local market in Dhaka, Bangladesh, captured using high-resolution microscopic cameras. This dataset features more than 200 images each from 10 different types of rice, totalling approximately 2010 images. After augmentation, the folders expanded to 800 images, totalling 8010 augmented images. Each of the images provides a detailed view of the structure of each rice grain after the milling process and shows the result of the polishing process, which proves the nutritional loss. The sole purpose of presenting the dataset is to prove the hidden impact of the milling process on rice and serve as a valuable resource for further study on rice quality and overall food security.}
}


# 4

@article{ISLAM2024110442,
title = {A visual dataset for recognition of rice varieties},
journal = {Data in Brief},
volume = {54},
pages = {110442},
year = {2024},
issn = {2352-3409},
doi = {https://doi.org/10.1016/j.dib.2024.110442},
url = {https://www.sciencedirect.com/science/article/pii/S2352340924004116},
author = {Md. Masudul Islam and Galib Muhammad Shahriar Himel and Mohammad Shorif Uddin and Md. Golam Moazzam},
keywords = {Image classification, Rice varieties, Computer vision, Deep learning},
abstract = {This article presents a comprehensive dataset sourced from various markets across Bangladesh, highlighting 20 distinct rice varieties predominantly consumed locally. The dataset encompasses a diverse range of rice strains, including Subol Lota, Bashmoti (Deshi), Ganjiya, Shampakatari, Sugandhi Katarivog, BR-28, BR-29, Paijam, Bashful, Lal Aush, BR-Jirashail, Gutisharna, Birui, Najirshail, Pahari Birui, Polao (Katari), Polao (Chinigura), Amon, Shorna-5, and Lal Binni. Using a smartphone camera, low-resolution images capturing the essence of each rice variety were meticulously obtained, resulting in a total of 4,730 images with a non-uniform distribution. The dataset also includes augmented data, totaling 23,650 images. This precisely curated dataset holds significant promise and utility, showcasing diverse attributes, including the unique representation of 20 rice varieties, each characterized by distinct colors, sizes, and potential applications within the agricultural sector.}
}


*Next Page (Global research trends)*
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.

































## Global Research Trends:

|  No.  | Title                                                                                                                      | Link                                                                                                                                                                              | Main Finding                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| :---: | :------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1** | _Rice Image Dataset (Kaggle Benchmark)_                                                                                    | [Link](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset/code?datasetId=2049052&sortBy=voteCount)                                                              | Contains **75,000 images** of **five Turkish rice varieties**. Showing different approaches people have taken for the classification.This dataset contains a total of **5 classes**, with 15,000 samples from each rice variety used by many other researches in the followed table.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **2** | _Identification of Rice Varieties Using Machine Learning Algorithms_                                                       | [Link](https://pdfs.semanticscholar.org/8ac9/fd361c69d508a068baa8e3c2bd8b4e3d7d5d.pdf)                                                                                            | Using the same 75k dataset, a **Multilayer Perceptron (MLP)** achieved **99.91% accuracy** with **106 hand-crafted features** (morphological, shape, and color-based).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **3** | _Rice Grain Classification Using Vision Transformer (ViT) Architecture_                                                    | [Link](https://www.preprints.org/manuscript/202510.1976)                                                                                                                          | **ViT** outperformed CNNs by capturing **global contextual relationships**, achieving **99.9984% accuracy** on the 75k image benchmark.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **4** | _Identification of Indian rice varieties using machine learning classifiers._                                              | [Link](https://www.cabidigitallibrary.org/doi/pdf/10.5555/20209904053)                                                                                                            | This study focused on identifying **eight Indian rice varieties** using a self-collected dataset. The dataset consisted of 100 samples for each variety, analyzed using six features like plant height and grain length, rather than imaging. The authors compared four machine learning models: Linear Discriminant Analysis, Logistic Regression, Naïve-Bayes, and **K-Nearest Neighbors (K-NN)**. The **K-NN classifier proved superior**, achieving **99.16% accuracy** and 99.12% precision and recall on the test data                                                                                                                                                                                                                                                                                                      |
| **5** | _Automatic Rice Variety Identification System: state-of-the-art review, issues, challenges and future directions_          | [Link](https://link.springer.com/article/10.1007/s11042-023-14487-x)                                                                                                              | This paper provides a comprehensive state-of-the-art review of automatic rice variety identification systems. It finds that most research has focused on machine learning (64% of studies) rather than deep learning (only 4%). A key finding is that using a **hybrid or mixed-feature approach** (combining features like morphological, color, and texture) significantly improves accuracy over single-feature methods. While the review doesn't propose one single best model, it highlights top-performing models from other studies, including an **ensemble classifier** that achieved **99.86% accuracy** and a **Convolutional Neural Network (CNN)** that reached **99.52%**. The paper concludes that deep learning and deep transfer learning are promising, under-explored areas for future research in this field. |
| **6** | _Quality Assessment of Rice Using Convolution Neural Networks and Other Machine Learning Techniques – A Comparative Study_ | [Link](http://www.agriculturejournal.org/volume12number2/quality-assessment-of-rice-using-convolution-neural-networks-and-other-machine-learning-techniques-a-comparative-study/) | On a **small dataset (800 samples)**, CNNs performed poorly (**68.2%**), while classical ML with **texture features** (e.g., SVM, Decision Trees) reached **96.75%**, showing deep learning’s weakness with low data.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **7** | _Rice Grain Detection and Counting Method Based on TCLE–YOLO Model_                                                        | [Link](https://www.researchgate.net/publication/375629177_Rice_Grain_Detection_and_Counting_Method_Based_on_TCLE-YOLO_Model)                                                      | Introduces **TCLE-YOLO**, a YOLOv5 variant with Transformer Encoder and Coordinate Attention. Achieved **99.2% mAP** for **dense, overlapping grains**.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
# 1 

https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset
# 2

@article{article,
author = {Cinar, Ilkay and Koklu, Murat},
year = {2021},
month = {05},
pages = {},
title = {Identification of Rice Varieties Using Machine Learning Algorithms},
volume = {28},
journal = {Tarım Bilimleri Dergisi},
doi = {10.15832/ankutbd.862482}
}


# 3 

@article{202510.1976,
	doi = {10.20944/preprints202510.1976.v1},
	url = {https://doi.org/10.20944/preprints202510.1976.v1},
	year = 2025,
	month = {October},
	publisher = {Preprints},
	author = {Shubham Singh and Sudeep Marwah and Rahul Neware and Akash Hosamani},
	title = {Rice Grain Classification Using Vision Transformer (ViT) Architecture},
	journal = {Preprints}
}

# 4 

@inproceedings{Dheer2019IDENTIFICATIONOI, title={IDENTIFICATION OF INDIAN RICE VARIETIES USING MACHINE LEARNING CLASSIFIERS}, author={Puneet Dheer and R. K. P. Singh}, year={2019}, url={https://api.semanticscholar.org/CorpusID:220279570} }

# 5
@article{article,
author = {Komal, and Sethi, Ganesh and Bawa, Rajesh},
year = {2023},
month = {02},
pages = {1-32},
title = {Automatic Rice Variety Identification System: state-of-the-art review, issues, challenges and future directions},
volume = {82},
journal = {Multimedia Tools and Applications},
doi = {10.1007/s11042-023-14487-x}
}


# 6

@article{article,
author = {Phukon, Nilutpal and Singh, Robert and Singh, Takhellambam and Datta, Subir and Deb, Subhasish and Singh, Usham and Thingbaijam, Ghaneshwori},
year = {2024},
month = {09},
pages = {762-772},
title = {Quality Assessment of Rice Using Convolution Neural Networks and Other Machine Learning Techniques- A Comparative Study},
volume = {12},
journal = {Current Agriculture Research Journal},
doi = {10.12944/CARJ.12.2.21}
}


# 7 

@article{article,
author = {yu, Zou and Tian, Zefeng and Cao, Jiawen and Ren, Yi and Zhang, Yaping and Liu, Lu and Zhang, Peijiang and Ni, Jinlong},
year = {2023},
month = {11},
pages = {9129},
title = {Rice Grain Detection and Counting Method Based on TCLE–YOLO Model},
volume = {23},
journal = {Sensors},
doi = {10.3390/s23229129}
}