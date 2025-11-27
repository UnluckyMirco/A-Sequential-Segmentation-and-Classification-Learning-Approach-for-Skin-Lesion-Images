# A-Sequential-Segmentation-and-Classification-Learning-Approach-for-Skin-Lesion-Images
This is the repository of the paper "A Sequential Segmentation and Classification Learning Approach for Skin Lesion Images", which contains the notebooks of the experiments presented in the paper. For each dataset considered, a short explanation and references are presented.

## HAM 10000 and its 7 classes

The HAM dataset consists of ten thousand images divided into seven classes: 
- **Melanoma** (MEL): Melanoma is a malignant neoplasm originating from melanocytes, the cells responsible for skin pigmentation. %It represents the most lethal form of skin cancer, characterized by high morphological variability and a tendency for early metastasis.

- **Melanocytic Nevi** (NV): Melanocytic nevi are benign lesions comprised of localized accumulations of melanocytes. %They are among the most common skin lesions, exhibiting a wide range of morphological appearances, typically circumscribed and with uniform pigmentation.

- **Basal Cell Carcinoma** (BCC): Basal cell carcinoma is the most common form of skin cancer, originating from the basal cells of the epidermal layer. %It is characterized by slow growth and a low risk of metastasis, typically manifesting as nodular or ulcerative lesions.

- **Actinic Keratoses** (AKIEC): Actinic keratoses are precancerous, scaly skin lesions induced by chronic exposure to ultraviolet rays. %They are considered precursors to squamous cell carcinoma and typically present as rough plaques on sun-exposed skin areas.

- **Benign Keratosis-like Lesions** (BKL): Benign keratosis-like lesions encompass a variety of benign conditions, such as seborrheic keratosis, sebaceous hyperplasia, and clear cell acanthoma. %An overgrowth of the keratin component of the epidermis characterizes these lesions.

- **Dermatofibroma** (DF): Dermatofibroma is a benign cutaneous nodule commonly resulting from a reaction to minor injuries or insect bites. %It typically presents as a firm, slightly raised lesion with a brown to reddish color.

- **Vascular Lesions** (VASC): Vascular lesions include a range of conditions characterized by abnormal proliferation or dilation of blood or lymphatic vessels. %Common examples are hemangiomas and vascular malformations. They typically present as red or purplish spots or nodules.

| Dataset |  Original classes | Selected images cardinality | Download link |
|:-----|:-----:|-----:|-----:|
| HAM 10000 [[1]](#1) | 7 | 10.015 | https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T |
| Kvasir-Classification [2] | 8 | 8.000 | https://datasets.simula.no/kvasir/ |
| Kvasir-Segmentation [3] | Polyp segmentation | 1.000 images + masks | https://datasets.simula.no/kvasir-seg/ |


## Cite
To ensure proper attribution, we kindly request you to cite our paper when using this information:
_add link to the paper once is published_
Currently acceptec at: "Biomedical Engineering" in the special issue: "AI-Based Biomedical Signal Processing—2nd Edition"


## References

<a id="1">[1]</a>
Tschandl, Philipp, Cliff Rosendahl, and Harald Kittler. "The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions." Scientific data 5.1 (2018): 1-9.
<a id="2">[2]</a>  
Pogorelov, K.; Randel, P.; de Lange, T.; Jha, D.; Johansen, D.; et al.  
Kvasir: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection.  
*Proceedings of the 8th ACM Multimedia Systems Conference*, **2017**, 164–169.  
Available online: https://datasets.simula.no/kvasir/.

<a id="3">[3]</a>  
Jha, D.; Smedsrud, P.H.; Riegler, M.A.; Johansen, D.; Halvorsen, P.; de Lange, T.  
Kvasir-SEG: Segmented polyp images dataset.  
*Proceedings of International Conference on Multimedia Modeling (MMM)*, **2020**, 451–462.  
Available online: https://datasets.simula.no/kvasir-seg/.
