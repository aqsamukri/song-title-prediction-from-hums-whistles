Song Title Prediction from Hums and Whistles

1. Project Overview: 
This project explores the use of machine learning techniques to classify movie theme songs from hummed and whistled audio recordings. 
The aim is to investigate how well simple audio features and classical machine learning models can distinguish between different songs based on non verbal human input.
The project was completed as part of an MSc Data Science coursework and focuses on the end-to-end machine learning workflow, from data preparation to model evaluation and analysis.

2.	Dataset: 
The dataset consists of approximately 400 audio recordings of hummed and whistled movie theme songs.
Audio samples were recorded by students, including variations in pitch, tempo, and recording style.
Labels correspond to different movie theme song categories.
The dataset is relatively small and intentionally noisy, reflecting real world variability.

3.	Methodology: 
The project follows a structured machine learning pipeline – 
(a)	Audio Processing & Feature Extraction -
Extracted time domain and frequency domain features from audio signals
Converted raw audio into numerical representations suitable for modelling
(b)	Exploratory Data Analysis (EDA) – 
Analysed feature distributions and class balance
Identified challenges related to overlapping feature spaces
(c)	Model Training & Validation –
 Used stratified train–validation–test splits
Standardised features using preprocessing pipelines

4.	Models Implemented:
The following supervised classification models were evaluated –
- k-Nearest Neighbours (KNN) 
- Random Forest
- Support Vector Machine (SVM with RBF kernel)
Models were compared using validation accuracy to select the best performing approach.

5.	Evaluation & Results:
Performance was assessed using accuracy, classification reports, and confusion matrices.
Overall accuracy was limited due to simple feature representations, dataset size, and high inter-class similarity.
Results highlighted the difficulty of song classification from humming and whistling using basic features.

6.	Limitations & Future Improvements:
Key limitations identified:
- Limited dataset size
- High variability in humming and whistling styles
- Simple, non-music-specific features
Potential improvements include:
- Using richer audio features such as MFCCs, chroma features, or mel-spectrograms
- Applying data augmentation techniques
- Exploring more advanced models, including deep learning approaches

7. Tools & Technologies:
- Python
- NumPy
- Pandas
- scikit-learn
- Librosa
- Matplotlib
- Seaborn

8. Key Skills Demonstrated:
- Machine Learning (Supervised Classification)
- Audio Data Processing
- Feature Engineering
- Exploratory Data Analysis
- Model Evaluation and Interpretation


