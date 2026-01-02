🌾 Agri-Sense – Smart Farming Assistant
Agri-Sense is an intelligent web application designed to empower farmers with data-driven insights for improved agricultural practices. By integrating machine learning, the platform offers real-time recommendations on crop selection, fertilizer usage, and disease detection, thereby enhancing productivity and sustainability.

🚀 Features
🌱 Crop Recommendation
Get intelligent crop suggestions based on soil parameters and environmental conditions.

🧪 Fertilizer Guidance
Receive customized fertilizer recommendations based on nutrient levels (NPK values) to optimize yield.

🦠 Disease Prediction
Upload images of crops to detect diseases and get treatment advice using deep learning models.

🖥️ Clean User Interface
Intuitive and responsive interface to ensure seamless interaction for users of all technical backgrounds.

🛠️ Tech Stack
Backend
Framework: Flask (Python)

ML Libraries: PyTorch, TensorFlow, Scikit-learn

Frontend
Technologies: HTML5, CSS3, Bootstrap 4, JavaScript

Others
API Integration: Weather API (configurable in config.py)

Database: (Not specified; assumed to be local/in-memory for now)

🔧 Installation & Setup
1. Clone the Repository
bash
'''git clone https://github.com/nithingowda381/Agri-Sense'''
'''cd Agri-Sense'''
2. Create a Virtual Environment
bash
'''python -m venv venv'''
# On Windows
'''venv\Scripts\activate'''
# On Linux/macOS
'''source venv/bin/activate'''
3. Install Dependencies
bash
'''pip install -r requirements.txt'''
4. Configure Environment
Open config.py and insert your Weather API key.

5. Launch the Application
bash
flask run
💡 Usage Guide
Crop Recommendation:
Enter soil details such as nitrogen, phosphorus, potassium, pH, and rainfall to get suitable crop suggestions.

Fertilizer Recommendation:
Provide soil NPK levels to get fertilizer usage advice.

Disease Detection:
Upload a leaf image; the system predicts the disease (if any) and offers treatment suggestions.

📁 Project Structure
graphql
<pre><code>```plaintext Agri-Sense/ │ ├── app.py # Main Flask application ├── config.py # API keys and configuration ├── requirements.txt # Python dependencies │ ├── utils/ # ML and logic modules │ ├── model.py # Image classification model │ ├── fertilizer.py # Fertilizer recommendation logic │ └── disease.py # Disease information and prediction │ ├── templates/ # HTML templates │ ├── layout.html # Base layout │ ├── index.html # Home page │ ├── crop.html # Crop recommendation page │ ├── fertilizer.html # Fertilizer recommendation page │ └── disease.html # Disease prediction page │ ├── static/ # Static files │ ├── css/ # CSS stylesheets │ └── images/ # App images ```</code></pre>

🤝 Contributing
We welcome contributions!
To contribute:

Fork the repository.

Create a new branch (feature/your-feature-name).

Submit a pull request with a clear explanation.

You can also report issues or request features using the Issues tab.

📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.

🙏 Acknowledgments
Special thanks to the open-source community.



