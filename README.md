# Restaurant Data Analysis - Cognifyz Internship

A comprehensive data science project analyzing restaurant data through machine learning, recommendation systems, and geospatial analysis.

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Tasks](#tasks)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

This project was completed as part of the Cognifyz Technologies Data Science Internship. It involves analyzing a comprehensive restaurant dataset to extract meaningful insights and build predictive models. The project is divided into four main tasks, each focusing on different aspects of data analysis and machine learning.

### Key Objectives

- Predict restaurant ratings using machine learning algorithms
- Build a content-based restaurant recommendation system
- Classify restaurants by cuisine types using multi-label classification
- Perform geospatial analysis to identify location-based patterns

## 📁 Project Structure

```
├── Dataset .csv                              # Restaurant dataset
├── Task_1_Rating_Prediction.ipynb           # Rating prediction model
├── Task_2_Recommendation_System.ipynb       # Restaurant recommendation system
├── Task_3_Cuisine_Classification.ipynb      # Cuisine classification model
├── Task_4_Geospatial_Analysis.ipynb        # Location-based analysis
├── restaurant_map.html                      # Interactive restaurant map
└── README.md                                # Project documentation
```

## 📊 Tasks

### Task 1: Restaurant Rating Prediction

**Objective:** Build a machine learning model to predict the aggregate rating of restaurants based on various features.

**Key Steps:**
- Data preprocessing and handling missing values
- Feature engineering and encoding categorical variables
- Training regression models (Linear Regression, Decision Tree)
- Model evaluation using MSE and R-squared metrics
- Feature importance analysis

**Technologies:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn

---

### Task 2: Restaurant Recommendation System

**Objective:** Create a content-based recommendation system to suggest restaurants based on user preferences.

**Key Steps:**
- Feature extraction from restaurant attributes
- TF-IDF vectorization for text features
- Cosine similarity computation
- Recommendation generation based on cuisine, price range, and ratings

**Technologies:** Scikit-learn, TF-IDF Vectorizer, Pandas

---

### Task 3: Cuisine Classification

**Objective:** Develop a multi-label classification model to predict restaurant cuisine types.

**Key Steps:**
- Multi-label data preparation using MultiLabelBinarizer
- Feature engineering with restaurant name, locality, and cost
- Pipeline creation with preprocessing and classification
- Multi-output classification using Logistic Regression
- Model evaluation with classification metrics

**Technologies:** Scikit-learn, MultiLabelBinarizer, Pipeline, LogisticRegression

---

### Task 4: Geospatial Analysis

**Objective:** Perform geographical analysis of restaurants to identify location-based patterns and insights.

**Key Steps:**
- Exploration of latitude and longitude coordinates
- Restaurant distribution visualization on interactive maps
- City and locality-based grouping and analysis
- Statistical analysis of ratings, cuisines, and price ranges by location
- Pattern identification and insight extraction

**Technologies:** Folium, Pandas, Matplotlib, Seaborn

## 🛠️ Technologies Used

### Programming Language
- Python 3.x

### Libraries & Frameworks
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** Scikit-learn
- **Visualization:** Matplotlib, Seaborn, Folium
- **Text Processing:** TF-IDF Vectorizer
- **Geospatial:** Folium for interactive maps

### Tools
- Jupyter Notebook
- Git & GitHub

## 💻 Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Setup Instructions

1. Clone the repository
```bash
git clone https://github.com/yourusername/restaurant-data-analysis.git
cd restaurant-data-analysis
```

2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required packages
```bash
pip install pandas numpy scikit-learn matplotlib seaborn folium jupyter
```

4. Launch Jupyter Notebook
```bash
jupyter notebook
```

## 🚀 Usage

### Running Individual Tasks

1. **Task 1 - Rating Prediction:**
   ```bash
   jupyter notebook Task_1_Rating_Prediction.ipynb
   ```
   Run all cells to train the rating prediction model and view results.

2. **Task 2 - Recommendation System:**
   ```bash
   jupyter notebook Task_2_Recommendation_System.ipynb
   ```
   Execute cells to build the recommendation system and get restaurant suggestions.

3. **Task 3 - Cuisine Classification:**
   ```bash
   jupyter notebook Task_3_Cuisine_Classification.ipynb
   ```
   Run the notebook to train the multi-label cuisine classifier.

4. **Task 4 - Geospatial Analysis:**
   ```bash
   jupyter notebook Task_4_Geospatial_Analysis.ipynb
   ```
   Execute to generate interactive maps and location-based insights.

### Dataset

The project uses a restaurant dataset (`Dataset .csv`) containing the following features:
- Restaurant ID, Name, and Location details
- Cuisines offered
- Average cost for two
- Price range
- Aggregate ratings and votes
- Online services availability
- Geographic coordinates (Latitude, Longitude)

## 📈 Results

### Task 1: Rating Prediction
- Successfully built regression models to predict restaurant ratings
- Identified key features influencing restaurant ratings
- Achieved satisfactory model performance metrics

### Task 2: Recommendation System
- Developed a functional content-based recommendation engine
- Successfully recommends similar restaurants based on user preferences
- Utilizes cuisine type, price range, and ratings for recommendations

### Task 3: Cuisine Classification
- Implemented multi-label classification for 142+ cuisine types
- Achieved reasonable accuracy in predicting restaurant cuisines
- Model handles multiple cuisine labels per restaurant

### Task 4: Geospatial Analysis
- Created interactive maps showing restaurant distributions
- Identified high-concentration restaurant areas
- Analyzed location-based patterns in ratings and cuisines

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourprofile)
- Email: your.email@example.com

## 🙏 Acknowledgments

- **Cognifyz Technologies** for providing the internship opportunity
- Dataset providers for the comprehensive restaurant data
- Open-source community for the amazing tools and libraries

---

⭐ If you found this project helpful, please consider giving it a star!

**Project Status:** Completed ✅

**Last Updated:** November 2025
