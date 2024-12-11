# Improving Historical Archive Transcription through Deep Learning Models and Data Augmentation (Senior Thesis Project)

Washington Dataset: check the zipped file 
Created Dataset: I could not upload it because the file was too big. https://drive.google.com/drive/folders/1dUnoVTzpF6ThdlTDuk89lTvuLWMLavIi?usp=sharing
Thesis zipped folder: It holds the generated ground truth texts for the created dataset. 

Main OCR Pipeline: It holds the code for the implemenation of my main OCR architecture. 
- all.txt: It holds the outputed transcript of the model. 
Resnet without UNet: It holds the code for the implemenation of my main OCR architecture without the UNet model part.
- justresnetall.txt: It holds the outputed transcript of the model. 
Tesseract for Creating a New Dataset: It holds the code to create the ground truths for my created dataset and how to crop the scanned images.
Tesseract on Washington Dataset: It holds the code to Tesseract applied to the Washington Dataset. 
Tesseract on Washington Dataset with preprocessing and data augmentation: It holds the code to Tesseract applied to the Washington Dataset with preprocessing and data augmentation. 


NOTE: Since I use Google Colab for my code to access GPUs, the paths to my folders lead to my folders on my Google Drive. To make the code run, please make sure to change the path to where you have downloaded the data. 
