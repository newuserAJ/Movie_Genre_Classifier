<h2>📌 Project Overview</h2>
<p>This project focuses on classifying movie genres based on textual data using the <strong>AdaBoost Classifier</strong>. By leveraging machine learning techniques, the model attempts to predict a movie’s genre based on features extracted from its metadata.</p>

<h2>📌 Features</h2>
<ul>
    <li><strong>Dataset</strong>: Includes movie titles, descriptions, and metadata.</li>
    <li><strong>Preprocessing</strong>: Tokenization, vectorization, and feature engineering.</li>
    <li><strong>Classifier</strong>: AdaBoost with decision stumps as weak learners.</li>
    <li><strong>Evaluation Metrics</strong>: Accuracy, confusion matrix, and classification report.</li>
</ul>

<h2>📊 Model Performance</h2>
<p>Despite rigorous feature engineering and hyperparameter tuning, the <strong>AdaBoost classifier achieved an accuracy of approximately 40%</strong>. While this performance suggests room for improvement, it highlights the complexity of movie genre classification due to overlapping features among genres.</p>

<h2>🚀 Future Enhancements</h2>
<ul>
    <li>Incorporate <strong>deep learning models</strong> (e.g., LSTMs or transformers) for better text representation.</li>
    <li>Experiment with <strong>other ensemble learning techniques</strong> like Random Forest or Gradient Boosting.</li>
    <li>Enhance dataset quality by including more metadata (e.g., actors, directors, audience ratings).</li>
</ul>

<h2>📁 Installation & Usage</h2>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/your-repo/movie-genre-classification.git</code></pre>
    </li>
    <li>Install dependencies:
        <pre><code>pip install -r requirements.txt</code></pre>
    </li>
    <li>Run the training script:
        <pre><code>python train.py</code></pre>
    </li>
    <li>Evaluate the model:
        <pre><code>python evaluate.py</code></pre>
    </li>
</ol>

<h2>🤝 Contributing</h2>
<p>Feel free to fork this repository and propose improvements! Any contributions towards boosting accuracy or refining features are welcome.</p>

<h2>🐜 License</h2>
<p>This project is open-source and available under the MIT License.</p>

<hr>
<p>🔍 <em>Even a 40% accuracy is a step towards learning! Keep experimenting and improving.</em> 🚀</p>
