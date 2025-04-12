Agri-Sense
Agri-Sense is a web application designed to assist farmers in making informed decisions about their farming strategies. By leveraging machine learning, it provides personalized recommendations for crop selection, fertilizer usage, and disease prediction.

Features
Crop Recommendation: Suggests the most suitable crops to grow based on soil conditions and environmental factors.
Fertilizer Recommendation: Provides tailored fertilizer advice based on soil nutrient levels.
Disease Prediction: Identifies potential crop diseases through image uploads and provides treatment suggestions.
User-Friendly Interface: Easy-to-navigate interface for a seamless user experience.
Technologies Used
Backend
Framework: Flask (Python)
Machine Learning Libraries: PyTorch, TensorFlow, Scikit-learn
Frontend
Technologies: HTML, CSS, Bootstrap, JavaScript
Others
Database: (Not specified; assumed to be in-memory or file-based)
APIs: Weather API (configurable via config.py)
Installation
Clone the repository:

bash
git clone https://github.com/nithingowda381/Agri-Sense
cd Agri-Sense
Create a virtual environment:

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install the required packages:

bash
pip install -r requirements.txt
Set up your environment variables:

Add your weather API key in the config.py file.
Run the application:

bash
flask run
Usage
Crop Recommendation: Input soil parameters and select the desired crop.
Fertilizer Recommendation: Enter nitrogen, phosphorus, and potassium levels for tailored advice.
Disease Prediction: Upload an image of crops to detect diseases and receive treatment suggestions.
File Structure
Code
Project/
│
├── utils/
│   ├── model.py          # Neural network model for disease prediction
│   ├── fertilizer.py     # Fertilizer recommendations based on soil nutrients
│   └── disease.py        # Disease information and recommendations
│
├── templates/
│   ├── layout.html       # Base layout for the web application
│   ├── index.html        # Home page
│   ├── crop.html         # Crop recommendation page
│   ├── fertilizer.html   # Fertilizer recommendation page
│   ├── disease.html      # Disease prediction page
│   └── ...               # Other HTML templates
│
├── static/
│   ├── css/              # CSS files for styling
│   └── images/           # Images used in the application
│
├── requirements.txt      # Python dependencies
├── config.py             # Configuration file for API keys and settings
└── app.py                # Main application file
Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any suggestions or improvements.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the contributors and the open-source community for their support and resources.
