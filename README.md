# Smart Travel Recommendation System

## Overview
The **Smart Travel Recommendation System** is a machine learning-based tool that provides personalized travel suggestions. This system incorporates **sentiment analysis** to enhance recommendations based on user feedback. The model was trained and executed using **Google Colab**.

## Features
- Personalized travel recommendations based on user preferences.
- Sentiment analysis to refine suggestions.
- Uses real-world datasets to enhance accuracy.
- Implemented using machine learning techniques.

## Project Structure
```
Smart-Travel-Recommendation-System/
│-- smart_travel_recommender_system.ipynb  # Jupyter Notebook with implementation
│-- Traveler_Trip_Dataset.csv              # Dataset used for training
│-- smart_travel_recommendation.pkl        # Trained model file
│-- requirements.txt                        # List of dependencies
│-- README.md                               # Project documentation
```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Smart-Travel-Recommendation-System.git
   cd Smart-Travel-Recommendation-System
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies
The required libraries are listed in `requirements.txt`:
```
pandas
numpy
requests
nltk
imblearn
scikit-learn
xgboost
pickle
```

## Usage
Open the Python Notebook and provided dataset on Google Colab and execute the code step by step:
1. Load and preprocess the dataset.
2. Train the model.
3. Perform sentiment analysis.
4. Generate travel recommendations.

Run the following command to launch Jupyter Notebook:
```bash
jupyter notebook smart_travel_recommender_system.ipynb
```

## Dataset
The dataset used for training is `Traveler_Trip_Dataset.csv`, which contains travel preferences and user feedback.

## Model
The trained machine learning model is stored as `smart_travel_recommendation.pkl`. You can load it in Python as follows:
```python
import pickle
with open('smart_travel_recommendation.pkl', 'rb') as model_file:
    model = pickle.load(model_file)
```

## Next Steps
- Improve model performance with additional data and feature engineering.
- Implement a web-based interface for easier user interaction.
- Optimize the sentiment analysis module for better recommendation accuracy.
- Explore deep learning models for enhanced recommendation precision.

## Author
**Viraj Surana**  
BTech in Data Science and Artificial Intelligence  
Indian Institute of Information Technology Dharwad

