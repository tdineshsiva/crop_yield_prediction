# Crop Yield Prediction using Multiple Machine Learning Algorithms and Flask Web Application

This project predicts crop yield based on environmental and agricultural parameters using multiple machine learning algorithms. The model is deployed using a Flask web application where users enter inputs (such as rainfall, temperature, soil nutrients, etc.) and receive a predicted crop yield instantly.

## Features
- Crop yield prediction using multiple ML algorithms
- Models compared: Linear Regression, SVM and others
- Flask web interface for easy user access
- Dynamic input form for yield prediction from user values
- Dataset preprocessing and feature engineering included

## Technologies Used
- Python
- Flask
- Scikit-learn (Linear Regression, SVM, etc.)
- Pandas, NumPy
- HTML, CSS (Web UI)

## How to Run
Install dependencies:  
pip install -r requirements.txt  

Run the Flask application:  
python app.py  

Open the browser and go to:  
http://127.0.0.1:5000  

Enter the required agricultural data in the form and click **Predict**.  
The system will display the predicted crop yield based on the trained ML model.

## Dataset Information
The dataset contains agricultural parameters including:  
- Temperature  
- Rainfall  
- Soil nutrients (N, P, K)  
- Humidity  
- Season / Crop type  
- Yield (target value)

The dataset was cleaned and preprocessed before model training to improve performance.

## Output
The application displays a numeric output representing the predicted yield for the given crop and environmental conditions.

## Applications
- Smart farming and Agri-tech systems
- Agricultural production forecasting
- Precision farming and crop decision support
- Government and research based crop prediction systems

## Citation (BibTeX)
If you use this project or its machine learning logic in your academic publication, please cite the following paper:

@article{dinesh2025crop,
  title={Sustainable Crop Yield Forecasting Using Advanced Machine Learning Techniques Based on Comprehensive Analysis of Soil Health Parameters and Environmental Factors},
  author={Dinesh, T and Siva Balan, A},
  journal={International Journal of Advanced Engineering and Management},
  volume={1},
  number={1},
  pages={13},
  year={2025},
  doi={10.65379/tpsn2013/ijaemsv01i01p4}
}

DOI Link: https://doi.org/10.65379/tpsn2013/ijaemsv01i01p4

If this project helped you, please star the repository to support the work.
