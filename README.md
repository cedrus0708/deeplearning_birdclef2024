# deeplearning_birdclef2024

Team name: Kesobb_kitaláljuk

Team members:
  
  - Bilicki Vilmos BLU8CF
  
  - Goldschmidt Olivér RXL623
  
  - Szabó Tamás János DN5FXS

Task: BirdCLEF 2024 
(https://www.kaggle.com/competitions/birdclef-2024/overview)

Files in the repository:
  - dl_milestone1.ipynb:
      In this file, we explore the metadata downloaded from the Kaggle website that we reach through Google Drive. We take a look at some of the images of the spectograms in the dataset.
      We make decisions about what attributes to keep, and we split the metadata into training (70%), validation (20%) and test (10%) datasets.
      We also discuss our ideas about further progress later on: we plan to split the spectrograms into smaller chunks (10 seconds for example) and we will use that to train our model.
  - dl_milestone2.ipynb:
      This is the file for Milestone 2. The notebook includes all neccessary code that should be run to train and evaluate the model.
  - dl_final_main.ipynb:
      This is the file of the final submission of our task. The whole process of data downloading, data preprocessing, model creation, training, validation and testing are in this notebook. The notebook is well-commented, helping understand the process of transforming data and training the model. The entire process of loading the data and training the modell can be recreated by running the notebook, but it's worth being aware that this is time and resource-intensive task, so we recommend running it on a GPU with at least the capacity of a T4. 
  - dl_final_demo.ipynb:
      The purpose of this notebook is to give an alternative to the main final notebook that can be run using less time and resources. We demonstrate how our data loading and model training works with 10 classes only, to give a proper insight into the structure but also remain time-efficient. 


