# medicinal-plant-identification
Machine Learning-based plant identification using Streamlit and PIL
This project aims to classify and identify various medicinal plants using image processing and machine learning. A user-friendly web app built with Streamlit allows users to upload a leaf image and get the plant's name and details instantly.
---
🎯 Project Objectives
Automate the identification of medicinal plants from leaf images.
Apply machine learning classification algorithms to image data.
Build a lightweight, interactive web app using Streamlit.
Aid users in recognizing herbal and ayurvedic plants for practical and research applications.
---
🧰 Tools & Technologies Used
Python
Machine Learning (Scikit-learn / TensorFlow / Keras)
Streamlit – for web app development
OpenCV / PIL – for image processing
NumPy, Pandas – for data manipulation
Matplotlib, Seaborn – for visualization
---
🔧 How to Use
Clone the repository or download the project files.
Install the required libraries:
bash
Copy
Edit
pip install -r requirements.txt
Launch the Streamlit app:
bash
Copy
Edit
streamlit run app.py
Upload an image of a medicinal plant leaf.
View the prediction result and plant details displayed on the app.
---
📘 Project Structure
bash
Copy
Edit
📁 medicinal-plant-identification/
├── app.py                  # Main Streamlit app
├── model.pkl               # Trained ML model
├── plant_dataset/          # Image dataset (categorized folders)
├── requirements.txt        # Python dependencies
├── utils.py                # Helper functions
└── README.md               # Project overview
---
🖼️ Workflow – Step-by-Step
Start
➡️ Dataset Collection (Images of medicinal plant leaves)
➡️ Image Preprocessing (Resize, Normalize, Augment)
➡️ Feature Extraction (CNN / ML pipeline)
➡️ Model Training and Evaluation
➡️ Save Model using Pickle or Joblib
➡️ Develop Streamlit App for UI
➡️ Upload Image ➡️ Predict ➡️ Display Result
End
---
🧪 Sample Output
Input Image	Predicted Class	Confidence
Neem (Azadirachta indica)	95.3%
---
💡 Future Scope
Expand dataset with more native Indian medicinal plants.
Integrate multilingual plant descriptions.
Add real-time mobile camera integration.
Deploy the app on cloud platforms (Heroku / Streamlit Cloud / AWS).
---
📚 References
Indian Medicinal Plant Databases
Research Papers on Leaf Image Classification
TensorFlow and Streamlit Documentation
