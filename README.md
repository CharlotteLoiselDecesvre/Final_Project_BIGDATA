# Final_Project_BIGDATA

Ana María Ramírez Bernal

Charlotte Loisel

Maria Marcela Martinez

Paloma Tejera Nevado

## Evaluation

Evaluation criteria:

* 5 points for the delivery of a meaningful Spark-based solution
* 2 points for the quality of the results obtained (using BigDL means a minimum of 1 point in this section).
* 2 points for style / code cleanliness / documentation
* 2 points for cross-evaluation of all members of the group among yourselves


# Pneumonia identification from X-Ray images

## Context

Pneumonia is an acute or chronic disease marked by inflammation of the lungs, usually caused by a bacterium, virus, or other infectious agent.

This disease can be detected through x-ray image analysis.

The normal chest X-ray depicts clear lungs without any areas of abnormal opacification in medical images. Bacterial pneumonia typically exhibits a focal lobar consolidation, whereas viral pneumonia manifests with a more diffuse ‘interstitial’ pattern in both lungs.

http://www.cell.com/cell/fulltext/S0092-8674(18)30154-5

## Data 

The data can be downloaded via this link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download.

The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. In order to account for any grading errors, the evaluation set was also checked by a third expert.

## Code

The notebook files Neural_Networks_X_Ray_Chest_V1.ipynb and Neural_Networks_X_Ray_Chest_V2.ipynb includes our codes. We tried to train BigDL-DLlib and Spark-based image classification models for predicting Pneumonia from the dataset presented above but we did not succeed it. For both codes, we had a size problem that we could not solve.
