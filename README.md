<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Machine Learning Project</h1>
    <p>This repository contains a Jupyter Notebook for a machine learning project.</p>
    <h2>Project Description</h2>
    <p>In this project, we perform various machine learning tasks using Python. The notebook includes data preprocessing, model training, and evaluation of different machine learning models including Decision Tree, KNN, and Regression.</p>
    <h2>Files</h2>
    <ul>
        <li><code>notebook.ipynb</code>: The main Jupyter Notebook file containing the code and results of the machine learning project.</li>
        <li><code>data/</code>: Directory containing the dataset(s) used in the project.</li>
    </ul>
    <h2>Installation</h2>
    <p>To run the notebook, you need to have Python and Jupyter Notebook installed. You can install the necessary packages using pip:</p>
    <pre><code>pip install numpy pandas scikit-learn jupyter</code></pre>
    <h2>Usage</h2>
    <ol>
        <li>Clone the repository to your local machine:</li>
        <pre><code>git clone https://github.com/yourusername/your-repository-name.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd your-repository-name</code></pre>
        <li>Launch Jupyter Notebook:</li>
        <pre><code>jupyter notebook</code></pre>
        <li>Open <code>notebook.ipynb</code> in the Jupyter Notebook interface.</li>
    </ol>
    <h2>Dataset</h2>
    <p>The dataset used in this project is <code>train.csv</code>, which is loaded from the Kaggle dataset. Make sure the dataset is placed in the <code>data/</code> directory.</p>
    <h2>Model Evaluation Results</h2>
    <p>Here are the evaluation results for the different models used in this project:</p>
    <table border="1">
        <tr>
            <th>Model</th>
            <th>Hyperparameter</th>
            <th>Train Accuracy</th>
            <th>Test Accuracy</th>
            <th>Train Precision</th>
            <th>Test Precision</th>
            <th>Train Recall</th>
            <th>Test Recall</th>
        </tr>
        <tr>
            <td>Decision Tree</td>
            <td>max_depth=5</td>
            <td>0.986</td>
            <td>0.986</td>
            <td>0.671</td>
            <td>0.615</td>
            <td>0.270</td>
            <td>0.263</td>
        </tr>
        <tr>
            <td>Decision Tree</td>
            <td>max_depth=8</td>
            <td>0.988</td>
            <td>0.985</td>
            <td>0.747</td>
            <td>0.551</td>
            <td>0.393</td>
            <td>0.295</td>
        </tr>
        <tr>
            <td>Decision Tree</td>
            <td>max_depth=10</td>
            <td>0.990</td>
            <td>0.985</td>
            <td>0.828</td>
            <td>0.557</td>
            <td>0.456</td>
            <td>0.324</td>
        </tr>
        <tr>
            <td>Decision Tree</td>
            <td>max_depth=15</td>
            <td>0.994</td>
            <td>0.983</td>
            <td>0.948</td>
            <td>0.467</td>
            <td>0.680</td>
            <td>0.356</td>
        </tr>
        <tr>
            <td>KNN</td>
            <td>n_neighbors=3</td>
            <td>0.988</td>
            <td>0.985</td>
            <td>0.787</td>
            <td>0.572</td>
            <td>0.327</td>
            <td>0.189</td>
        </tr>
        <tr>
            <td>KNN</td>
            <td>n_neighbors=5</td>
            <td>0.986</td>
            <td>0.985</td>
            <td>0.795</td>
            <td>0.723</td>
            <td>0.170</td>
            <td>0.137</td>
        </tr>
        <tr>
            <td>KNN</td>
            <td>n_neighbors=7</td>
            <td>0.986</td>
            <td>0.985</td>
            <td>0.775</td>
            <td>0.653</td>
            <td>0.151</td>
            <td>0.112</td>
        </tr>
        <tr>
            <td>KNN</td>
            <td>n_neighbors=9</td>
            <td>0.986</td>
            <td>0.985</td>
            <td>0.748</td>
            <td>0.659</td>
            <td>0.146</td>
            <td>0.128</td>
        </tr>
        <tr>
            <td>Regression</td>
            <td>Regression</td>
            <td>0.985</td>
            <td>0.764</td>
            <td>0.025</td>
            <td>0.984</td>
            <td>0.818</td>
            <td>0.021</td>
        </tr>
    </table>
</body>
</html>
