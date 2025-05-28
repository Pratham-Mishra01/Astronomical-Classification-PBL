# Stellar-Classification-PBL
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astronomical Object Classification Using Machine Learning - README</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; background-color: #f9f9f9; color: #333; }
        h1 { color: #2c3e50; }
        h2 { color: #34495e; margin-top: 1.5em; }
        ul { margin-left: 1.5em; }
        .container { max-width: 800px; margin: auto; background: white; padding: 24px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .section { margin-bottom: 2em; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Astronomical Object Classification Using Machine Learning</h1>
        
        <div class="section">
            <h2>Project Overview</h2>
            <p>
                This project aims to automate the classification of astronomical objects—specifically stars, galaxies, and quasars—using machine learning techniques.
                Leveraging labeled data from large sky surveys, the project demonstrates an end-to-end pipeline from raw data preprocessing to model training, evaluation, and result visualization in a Jupyter notebook environment.
            </p>
        </div>
        
        <div class="section">
            <h2>Key Features</h2>
            <ul>
                <li><strong>Data Preprocessing:</strong> Cleans, scales, and encodes features for optimal model performance.</li>
                <li><strong>Machine Learning Models:</strong> Implements and compares multiple classification algorithms, including Decision Tree, Random Forest, and Artificial Neural Network (ANN).</li>
                <li><strong>Evaluation:</strong> Uses metrics such as accuracy, precision, recall, F1-score, and confusion matrices to assess model performance.</li>
                <li><strong>Visualization:</strong> Plots training and validation curves, as well as key results for model interpretation.</li>
            </ul>
        </div>
        
        <div class="section">
            <h2>Dataset</h2>
            <p>
                The dataset consists of astronomical survey data with features such as right ascension, declination, photometric magnitudes (u, g, r, i, z), redshift, and class labels.
                <br>
                <strong>raw_data.csv:</strong> Contains the original features from the astronomical survey.<br>
                <strong>labeled_data.csv:</strong> Includes class labels for supervised learning (e.g., 0 = Galaxy, 1 = QSO, 2 = Star).
            </p>
        </div>
        
        <div class="section">
            <h2>Results</h2>
            <p>
                Achieved high classification accuracy with multiple machine learning models. Training and validation curves indicate strong model generalization and robust learning. 
                Key features influencing classification include photometric bands and redshift.
            </p>
        </div>
    </div>
</body>
</html>

