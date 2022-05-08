# CH5650: Molecular Data Science and Informatics
Repository containing the files used while completing the course project of CH5650: Molecular Data Science and Informatics offered at IIT Madras during the Jan-May 2022 semester. This project aimed at recreating the results of the paper titled "Insightful classification of crystal structures using deep learning" (DOI: 10.1038/s41467-018-05169-6) [1] and extending the work to use unsupervised learning techniques to perform crystal structure classification. The report for the project is titled "MM19B057_Report.pdf", the jupyter (technically Colab) notebook to recreate the results is titled "CH5650:CNN_classify.ipynb" and for the unsupervised learning part of the project is titled "CH5650:Unsupervised_Classify.ipynb". The trained CNN model is saved as "Trained_CNN.hdf5". The data used for this project was taken from the original work [1], and is hosted on the following links:

Pristine dataset (Diffraction fingerprints of crystals): 
https://dataverse.harvard.edu/api/access/datafile/3238702?format=original

Pristine dataset (Labels of crystals): 
https://dataverse.harvard.edu/api/access/datafile/3238704?format=original

Dataset info:
https://dataverse.harvard.edu/api/access/datafile/3238706?format=original

Defected dataset (Diffraction fingerprints of defected crystals):
https://dataverse.harvard.edu/api/access/datafile/3238702?format=original

Defected dataset (Labels of defected crystals):
https://dataverse.harvard.edu/api/access/datafile/3238704?format=original

References:
[1] A. Ziletti, D. Kumar, M. Scheffler, and L. M. Ghiringhelli,
        “Insightful classification of crystal structures using deep learning”,
        Nature Communications, vol. 9, pp. 2775 (2018)
