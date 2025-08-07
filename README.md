# Undergraduate Independent Research Project: Sex Bias in Autism Spectrum Disorder

![image](https://github.com/user-attachments/assets/25bc8055-8ae6-4d41-971a-fcdd59532ac6)

This is a respository for the source code for my undergraduate research topic of Autism and behavioral analysis. All code is under the format of Jupyter Notebook. The data used is from Autism Brain Imaging Data Exchange (ABIDE): https://fcon_1000.projects.nitrc.org/indi/abide/ 


### Abstract: 

Autism Spectrum Disorder (ASD) is a neurodevelopmental disorder that is characterized by repetitive behaviors, specific interests, or difficulty with social interactions. These symptoms have varying severity across individuals. In 2020, one out of thirty-six children were diagnosed with ASD as reported by the Centers for Disease Control and Prevention in the US. To address the high prevalence of ASD among children, research shows thatearly intervention is essential to reduce the severity of symptoms. Current diagnostic methods using behavioral assessments require a specialist evaluation, leading to an average wait of three years. Recent studies attempted to use published MRI scans to build an Autism classification model to expedite the diagnosis process. However, the classification model’s training requires scans from diagnosed ASD patients and contains a disproportionate ratio of males to females. Such bias could result in inferior classifications for female subjects. We propose to address the sampling bias by calibrating the severity scores from behavioral assessments alongside MRI scans across the sexes. Using the calibration method, we can build a classification model that improves the diagnostic results of female subjects. 
<img width="958" alt="image" src="https://github.com/user-attachments/assets/9a6aeb19-334c-4184-9992-adbeb4c141c3">


## Additional info

K-nearest Neighbors (KNN): it is a non-parametric supervised learning classifier. It uses proximity to classify new data points into groups.  Instance-based learning (compared to model-based models): instance-based models learn from examples, and make predictions by finding similar examples in the training data, while model-based models learn the underlying relationships and patterns in the data by creating a mathematical representation. As the dataset becomes increasingly complex, the model doesn't perform as well. Pick an odd k number to avoid ties. Works well to impute data when we have missing data points. 
