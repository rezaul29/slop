
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


