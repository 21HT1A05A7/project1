# project1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>House Price Prediction Project</title>
</head>
<body>

<h1>🏠 House Price Prediction Project</h1>

<section>
    <h2>Table of Contents</h2>
    <ol>
        <li>Acknowledgements</li>
        <li>Project Overview</li>
        <li>Dataset Description</li>
        <li>Project Structure</li>
        <li>Technology Stack</li>
        <li>Implementation Steps</li>
        <li>Code Explanation</li>
        <li>Model Development</li>
        <li>Deployment Process</li>
        <li>Results and Output</li>
        <li>Challenges and Solutions</li>
        <li>Future Enhancements</li>
        <li>Conclusion</li>
        <li>References</li>
    </ol>
</section>

<section>
    <h2>1. Acknowledgements</h2>
    <h3>Dataset Source</h3>
    <ul>
        <li><b>Dataset:</b> House Sales in King County, USA</li>
        <li><b>Source:</b> Kaggle</li>
        <li><b>Contributor:</b> Shreya Chaudhary</li>
        <li><b>Time Period:</b> May 2014 – May 2015</li>
    </ul>

    <h3>Tools and Libraries</h3>
    <ul>
        <li>Flask</li>
        <li>Scikit-learn</li>
        <li>NumPy</li>
        <li>Pandas</li>
        <li>Pickle</li>
        <li>HTML & CSS</li>
        <li>Render</li>
        <li>Git & GitHub</li>
    </ul>
</section>

<section>
    <h2>2. Project Overview</h2>
    <p>
        This project develops a machine learning web application that predicts house prices
        using features like location, size, condition, and date of sale.
    </p>

    <h3>Key Features</h3>
    <ul>
        <li>User-friendly web interface</li>
        <li>Real-time house price prediction</li>
        <li>17 input features</li>
        <li>Deployed and publicly accessible</li>
    </ul>
</section>

<section>
    <h2>3. Dataset Description</h2>
    <ul>
        <li>Total Records: 21,613</li>
        <li>Total Features: 18</li>
        <li>Location: King County, Washington, USA</li>
    </ul>

    <h3>Preprocessing Steps</h3>
    <ol>
        <li>Handling missing values</li>
        <li>Date feature extraction (year, month, day)</li>
        <li>Encoding categorical variables</li>
        <li>Feature selection</li>
    </ol>
</section>

<section>
    <h2>4. Project Structure</h2>
    <pre>
House-Price-Prediction/
│
├── app.py
├── MINI_PROJECT.pkl
├── requirements.txt
├── Procfile
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── README.html
    </pre>
</section>

<section>
    <h2>5. Technology Stack</h2>
    <h3>Backend</h3>
    <ul>
        <li>Python</li>
        <li>Flask</li>
        <li>Scikit-learn</li>
        <li>NumPy</li>
        <li>Pandas</li>
    </ul>

    <h3>Frontend</h3>
    <ul>
        <li>HTML5</li>
        <li>CSS3</li>
    </ul>

    <h3>Deployment</h3>
    <ul>
        <li>Render</li>
        <li>Gunicorn</li>
    </ul>
</section>

<section>
    <h2>6. Implementation Steps</h2>
    <h3>Environment Setup</h3>
    <pre>
python -m venv venv
venv\Scripts\activate
pip install flask numpy pandas scikit-learn gunicorn
    </pre>
</section>

<section>
    <h2>7. Code Explanation</h2>
    <p>
        A custom Linear Regression model is implemented using NumPy and Singular Value Decomposition (SVD),
        avoiding direct use of sklearn’s regression model.
    </p>
    <ul>
        <li>Manual label encoding</li>
        <li>Train-test split</li>
        <li>RMSE and R² score evaluation</li>
    </ul>
</section>

<section>
    <h2>8. Model Development</h2>
    <p>
        Linear Regression was chosen due to its simplicity, interpretability,
        and effectiveness for continuous target variables.
    </p>
</section>

<section>
    <h2>9. Deployment Process</h2>
    <ol>
        <li>Create GitHub repository</li>
        <li>Connect repository to Render</li>
        <li>Configure Python environment</li>
        <li>Deploy using Gunicorn</li>
    </ol>
</section>

<section>
    <h2>10. Results and Output</h2>
    <p>
        Sample Output: <b>Estimated House Price: 383,201.28</b>
    </p>
</section>

<section>
    <h2>11. Challenges and Solutions</h2>
    <ul>
        <li>Feature encoding handled using label encoding</li>
        <li>Model persistence achieved with Pickle</li>
        <li>Deployment issues resolved with proper requirements.txt</li>
    </ul>
</section>

<section>
    <h2>12. Future Enhancements</h2>
    <ul>
        <li>Advanced regression models</li>
        <li>Hyperparameter tuning</li>
        <li>Improved UI and data visualization</li>
    </ul>
</section>

<section>
    <h2>13. Conclusion</h2>
    <p>
        This project demonstrates a complete end-to-end machine learning pipeline,
        from data preprocessing to deployment as a web application.
    </p>
</section>

<section>
    <h2>14. References</h2>
    <ul>
        <li>Flask Documentation</li>
        <li>Scikit-learn Documentation</li>
        <li>Render Documentation</li>
        <li>Kaggle Dataset</li>
    </ul>
</section>

<footer>
    Project By: T. Nagalakshmi <br>
    Last Updated: 10-02-2026
</footer>

</body>
</html>
