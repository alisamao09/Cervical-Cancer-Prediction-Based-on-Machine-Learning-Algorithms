# Cervical-Cancer-Prediction-Based-on-Machine-Learning-Algorithms

## Overview
One of the main fatal diseases that threats women’s health is Cervical Cancer, which usually does not present any symptoms in early stages. When some symptoms appear, the patients’ condition might have been worsened and the cancer may have become metastatic. Therefore, early diagnosis of Cervical cancer
risk factors can stop its tracks and reduce the mortality rate and the associated complications.
To seek for more accurate earlier diagnosis, we proposed a study of Cervical cancer diagnosis based on machine learning classification using Support Vector Classifier, Kernel Ridge regression, Logistic Regression, Lasso Regression, Random Forest Classifier, Gradient Boosting Classifier, and Multilayer Perceptron. The dataset has around 30 variables describing over 800 patients’ demographic information, habits, and historic medical records. It includes four targets (Hinselmann, Schiller, Cytology, and Biopsy). The four targets are used as the measurement for cancer predictions in this project. We also used SMOTE method to handle the imbalanced dataset. Evaluation metrics include Mean Squared Error, R squared, precision, recall, F1 score, and Area Under Curve. Our results show that the Multilayer Perceptron yields the best performance for Hinselmann, and the Gradient Boosting Classifier yields the best performance for the other three targets when compared with other machine learning methods. Future work includes the application of these machine learning methods to a more balanced and real large scale hospital dataset and the inclusion of more informationrich features.
## Main process
* In this project, we will employ seven machine learning algorithms to predict the probability of the patients suffering from Cervical Cancer using sociodemographic factors and their pathological features and medical conditions. While relevant mathematical equations and variables for all models used are shown, the external library, sklearn, was imported and used for actual implementation due to its prior optimization with respect to the Python coding language in addition to the availability of built-in evaluation functions. In addition, we will measure the interpretability and predictability of the models and labels with or without Cervical Cancer by Mean Squared Error, R2, Area Under Curve, precision, recall, and F1 score. This will be further elaborated in the Evaluation section.

## Interpretation and significance of the final model
From this study, we suggest people, especially women, take HPV vaccine, take good care of personal life, especially sex life to prevent suffering from and transmitting sexual diseases, prevent wearing IUDs for a long time (several years) and take good precautions during sexual intercourse, and disclose more medical and sociodemographic information anonymously for data analysis use.

## Analysis limitations and potential
Although our model results show relatively low test error, high R2 and AUC for all test cases, and high precision, recall, and F1 score for positive test
cases, there are other factors we did not consider such as educational level and annual household income, etc. Besides, our sample size is relatively small and imbalanced, further training and testing on larger, balanced, and real datasets, especially on hospital datasets will be ideal. After applying the selected models to the proposed dataset, it is possible that this study to be used in future Cervical Cancer prediction analysis and improve the accuracy of early diagnostics. In addition, if time permits, we could find the key features that contribute to the above key factors by matrix mining and machine learning methods and suggest potential precautions.

## References
[1] World Cancer Report 2014. World Health Organization. 2014. pp. Chapter 5.12. ISBN 978- 9283204299.

[2] ”Cervical cancer prevention and control saves lives in the Republic of Korea”. World Health Organization.

[3]World Health Organization (February 2014). ”Fact sheet No. 297: Cancer”.

[4] Lei J, Ploner A, Elfstr¨om KM, Wang J, Roth A, Fang F, et al. HPV vaccination and the risk of invasive cervical cancer. N Engl J Med. 2020;383:1340–8.

[5] Williams EA, Newberg J, Williams KJ, Montesion M, Alexander BM, Lin DI, et al. Prevalence of High-Risk nonvaccine human papillomavirus types in advanced squamous cell carcinoma among individuals of african vs Non-African ancestry. JAMA Netw Open. 2021;4:e216481.

[6] ”Cervical Cancer Treatment (PDQ®)”. NCI. 14 March 2014.

[7] Huang H, Feng YL, Wan T, Zhang YN, Cao XP, Huang YW, et al. Effectiveness of sequential chemoradiation vs concur-rent chemoradiation or radiation alone in adjuvant treatment after hysterectomy for cervical cancer: the STARS phase 3 randomized clinical trial. JAMA Oncol. 2021;7:361–9.

[8] Arbyn M, Weiderpass E, Bruni L, de Sanjos´e S, Saraiya M, Ferlay J, et al. Estimates of incidence and mortality of cervi-cal cancer in 2018: a worldwide analysis. Lancet Glob Health. 2020;8:e191-203.

[9] Al-Wesabi Y.M.S., Choudhury A: Classification of Cervical Cancer Dataset. In: Proceedings of the 2018 IISE Annual Conference. Edited by K. Barker, D. Berry, C. Rainwater: 2018; Orlando: IISE; 2018:1456-1461.

[10] Khan, I.U., Aslam, N., Alshehri, R., Alzahrani, S., Alghamdi, M., Almalki, A., Balabeed, M., 2021. Cervical Cancer Diagnosis Model Using Extreme Gradient Boosting and Bioinspired Firefly Optimization. Scientific Programming 2021, 1–10. doi:10.1155/2021/5540024.

[11] Deng, X., Luo, Y., Wang, C., 2018. Analysis of Risk Factors for Cervical Cancer Based on Machine Learning Methods. doi:10.1109/ccis.2018.8691126.

[12] Scikit-learn: Machine Learning in Python, Pedregosa et al., JMLR 12, pp. 2825-2830, 2011.
