🌾 Crop Recommender System Using Machine Learning Approach
This project aims to assist farmers and agricultural planners in making data-driven decisions about which crops to grow, based on specific environmental and regional factors such as soil type, area, and state. By leveraging machine learning algorithms, the system can both recommend suitable crops and predict crop yield.

🚀 Features
📌 Crop Recommendation based on:

     . State

     . Area
     
     . Soil Type

📈 Crop Yield Prediction for:

    .Selected Crop

    .Specific Area
    
    .State and Soil Type

🔍 Machine Learning models for recommendation and regression-based prediction.

🌐 Multi-platform interface using Python, HTML, CSS, and JavaScript.

🛢️ Backend support with MySQL database.

🧠 Machine Learning Approach
Two major modules are implemented:

Crop Recommendation Module:

  Algorithm: Random Forest Classifier
  
  Input: State, Area, Soil Type
  Output: List of recommended crops with high yield potential

Crop Yield Prediction Module:

  Algorithm: Random Forest Regressor
  
  Input: State, Crop, Area, Soil Type
  Output: Predicted crop yield (in kg/ha)

🗃️ Dataset
Source: Collected from Indian agricultural datasets and soil data repositories.

Attributes:

State Name

Crop Name

Area (in hectares)

Soil Type

Crop Yield (in kg/ha)

🛠️ Tech Stack

    Frontend => HTML, CSS, JavaScript
    
    Backend	=> Python (Flask)
    
    Database => MySQL
    
    Machine Learning => Scikit-learn

🧪 How to Run the Project

Clone the repository:

git clone https://github.com/VikasReddy28/Crop-recommender-System-Using-ML.git

cd crop-recommender-system

Install dependencies:

pip install -r requirements.txt

Set up the database:

Create a MySQL database.

Import schema.sql and data.sql if provided.

Update the database configuration in the Python backend.

Run the Flask server:

python manage.py

Open in browser:

Navigate to http://localhost:5000 in your browser.

📊 Example Inputs

Crop Recommendation:

Input: Andhra Pradesh, 4 hectares, Alluvial soil

Output: Cotton, Groundnut, Paddy

Crop Yield Prediction:

Input: Karnataka, Maize, 5 hectares, Red soil

Output: Predicted yield: 3250 kg/ha

📚 Future Enhancements:

🌐 Integration with GPS/location services for real-time recommendations

📱 Mobile App version

🌧️ Inclusion of weather and rainfall data for dynamic prediction

🧪 More diverse datasets for wider applicability

