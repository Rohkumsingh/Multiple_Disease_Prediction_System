<h1 align="center">Multiple Disease Prediction System</h1>

<h2>Overview</h2>
<p>This is a Streamlit-based web application that predicts three different diseases using machine learning models:</p>
<ul>
  <li>Diabetes Prediction</li>
  <li>Heart Disease Prediction</li>
  <li>Parkinson's Disease Prediction</li>
</ul>
<p>The application uses pre-trained machine learning models loaded from <code>.sav</code> files to make predictions based on user input.</p>

<h2>Features</h2>
<ul>
  <li><strong>User-friendly Interface</strong>: Clean and intuitive design with a sidebar navigation</li>
  <li><strong>Multiple Disease Prediction</strong>: Three different prediction models in one application</li>
  <li><strong>Responsive Layout</strong>: Adapts to different screen sizes</li>
  <li><strong>Input Validation</strong>: Ensures proper data types are entered</li>
</ul>

<h2>Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Streamlit (for web interface)</li>
  <li>Scikit-learn (for machine learning models)</li>
  <li>Pickle (for model serialization)</li>
</ul>

<h2>Installation</h2>

<h3>Prerequisites</h3>
<ul>
  <li>Python 3.7 or higher</li>
  <li>pip (Python package installer)</li>
</ul>

<h3>Steps</h3>
<ol>
  <li>Clone the repository:
    <pre><code>git clone https://github.com/Rohkumsingh/Multiple_Disease_Prediction_System.git</code></pre>
  </li>
  <li>Navigate to the project directory:
    <pre><code>cd Multiple_Disease_Prediction_System</code></pre>
  </li>
  <li>Install the required packages:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>

<h2>File Structure</h2>
<pre>
Multiple_Disease_Prediction_System/
├── SAV Files/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
├── main.py
├── requirements.txt
└── README.md
</pre>

<h2>How to Run</h2>
<ol>
  <li>Ensure all model files (.sav) are in the <code>SAV Files</code> directory</li>
  <li>Run the application:
    <pre><code>streamlit run main.py</code></pre>
  </li>
  <li>The application will open in your default web browser at <code>http://localhost:8501</code></li>
</ol>

<h2>Usage</h2>
<ol>
  <li>Select the type of prediction you want to make from the sidebar</li>
  <li>Fill in all the required health parameters</li>
  <li>Click the "Test Result" button</li>
  <li>View the prediction result</li>
</ol>

<h2>Models Information</h2>
<ul>
  <li><strong>Diabetes Prediction</strong>: Uses parameters like Glucose level, BMI, Age, etc.</li>
  <li><strong>Heart Disease Prediction</strong>: Uses parameters like Age, Cholesterol level, Blood Pressure, etc.</li>
  <li><strong>Parkinson's Prediction</strong>: Uses voice measurement parameters like jitter, shimmer, etc.</li>
</ul>

<h2>Note</h2>
<ul>
  <li>This application is for educational/demonstration purposes only</li>
  <li>Predictions should not be considered as medical diagnosis</li>
  <li>Always consult with healthcare professionals for medical advice</li>
</ul>

<h2>License</h2>
<p>This project is open-source and available under the <a href="LICENSE">MIT License</a>.</p>
