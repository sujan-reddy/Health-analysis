# Health Analysis with AI

## Inspiration

Modern health reports contain a plethora of health data, which is often too complex for humans to conduct an in-depth analysis. However, computers have the potential to analyze numerous data points and predict diseases that are likely to occur. This has the potential to save lives and reduce the cost of diagnostics significantly.

## What it does

Our model is designed to take multiple health report data and combine them to provide a cohesive view of the dataset. It then performs predictive analysis to identify potential future health complications.

## How we built it

Our project involved the following steps:

1. **Data Gathering**: We collected various datasets from Kaggle, including CT scans with abnormalities and CSV files containing data for multiple diseases.

2. **Model Development**: We trained a U-Net model to classify CT scans with abnormalities and generate a 3D model. Additionally, we implemented transfer learning using VGG16, which is a pre-trained model.

3. **Machine Learning Models**: We employed various machine learning models from scikit-learn, some of which were hyper-tuned to optimize their performance.

## Challenges we ran into

During the project, we encountered several challenges, including:

- **Image Feature Extraction**: Extracting meaningful features from images proved to be a complex and challenging task.
- **Model Selection**: Selecting the most suitable pre-trained model for transfer learning was a challenging decision, as it greatly influences the model's performance.

## Accomplishments that we're proud of

We are proud to report that our model can successfully predict future diseases with an accuracy rate of 88%. Additionally, it generates predictive health reports, which is a significant achievement.

## What we learned

Throughout this project, we gained valuable insights into various aspects, including:

- **Implementation of Transfer Learning**: We learned how to apply transfer learning techniques to improve the performance of our models.
- **Usage of scikit-learn Models**: We gained experience in working with various machine learning models available in scikit-learn.
- **Exploratory Data Analysis**: We developed skills in exploring and understanding complex health datasets.

## What's next for Multi-level Health Analysis using Reports

We believe that our project can make a substantial impact in the health diagnostic space. By lowering costs and improving the accuracy of diagnoses and reports, we aim to further develop and expand this system to benefit more people in need of efficient and accurate health analysis.
