<br>1.The inception.py file is basically the INCEPTION/GOOGLENET architecture model being run on Kaggle Tumor Dataset classifying the MRI IMAGES into 4 classes namely-GLIOMA, PITUITARY , MENINGIOMA and NO TUMOR.</br>
<br>2.The same INCEPTION-V1 architecture was also trained on the OASIS ALZHEIMERS DATASET.</br>
<br>3.The model performed well with approx. 89% and 98% accuracy metrics respectively.</br>
<br>4.Transfer Learning method was used, VGG16 Conv Base was retrained with Acute Ischemic Stroke Patients(derived from Aster Hospital data).</br>
<br>5.The accuracy achieved was 99%.</br>
<br>6.Using the Inception v1 Module as Conv Base and retraining on Stroke patient's data produced similar results.Verification for Overfitting still underway.</br>
<br>Completed Frontend for uploading MRI images for 4 tumor classes, this encodes image into base64 string, passes it to ROXIE query,receives JSON response -predicted class with probability.</br>
