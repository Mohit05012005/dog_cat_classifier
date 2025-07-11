🐱🐶 Cat vs Dog Classifier
A simple Streamlit web app that uses a trained CNN model to classify images as either a cat or a dog. Upload your own image and see what the model predicts!

<!-- Optional GIF or image preview -->

🚀 Features
📤 Upload images in JPG, JPEG, or PNG format

🧠 Uses a pre-trained Convolutional Neural Network (CNN)

🔍 Shows predicted label and confidence

☁️ Automatically downloads the model from Google Drive if not present

🖼️ Responsive layout using Streamlit

📦 Requirements
Install the required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt should include:

txt
Copy
Edit
streamlit
tensorflow
Pillow
gdown
numpy
🛠 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/cat-vs-dog-classifier.git
cd cat-vs-dog-classifier
Run the Streamlit app:

bash
Copy
Edit
streamlit run app.py
Open the app in your browser
Streamlit will automatically open http://localhost:8501

📁 Project Structure
bash
Copy
Edit
.
├── app.py                # Main Streamlit app
├── model.h5              # CNN model (auto-downloaded from Google Drive)
├── requirements.txt      # Python dependencies
└── README.md             # Project description
📥 Model Info
If model.h5 is not present, it will be automatically downloaded from:

Google Drive Link

🧠 The model is trained on the Dogs vs Cats dataset from Kaggle.

📸 Example Output
Upload this image:

<img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg" width="200"/>
Prediction:

makefile
Copy
Edit
Prediction: Cat
Confidence: 0.91
🙋‍♂️ Author
Mohit Bohra

📧 Reach me on LinkedIn or GitHub

📄 License
This project is licensed under the MIT License