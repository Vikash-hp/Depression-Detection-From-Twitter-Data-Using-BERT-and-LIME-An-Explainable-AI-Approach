<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
</head>
<body>

  <h1>Depression Detection From Twitter Data Using BERT and LIME: An Explainable AI Approach</h1>

  <div class="section">
    <p>This project implements a depression detection system using <strong>BERT</strong> for classification and <strong>LIME</strong> for explainability. It analyzes tweets to determine if a user is likely experiencing depression, with visual interpretations for transparency.</p>
  </div>

  <div class="section">
    <h2>✨ Features</h2>
    <ul>
      <li>Text Preprocessing for tweet data</li>
      <li>BERT-based Classification</li>
      <li>LIME Explanations for interpretability</li>
      <li>Class Imbalance Handling</li>
      <li>Performance Metrics: Classification Report & Confusion Matrix</li>
      <li>Visualization of data and results</li>
    </ul>
  </div>

  <div class="section">
    <h2>⚙️ Prerequisites</h2>
    <p>Python 3.8+ with the following libraries:</p>
    <pre><code>pandas
numpy
torch
transformers
sklearn
matplotlib
seaborn
nltk
swifter
lime
evaluate
datasets</code></pre>
    <p>Install with:</p>
    <pre><code>pip install -r requirements.txt</code></pre>
  </div>

  <div class="section">
    <h2>📁 Dataset</h2>
    <p>The dataset <code>Training.csv</code> must include:</p>
    <ul>
      <li><strong>user_id</strong>: Unique user identifier</li>
      <li><strong>tweets</strong>: Semicolon-separated list of tweets</li>
      <li><strong>status</strong>: "Depression" or "Normal"</li>
    </ul>
  </div>

  <div class="section">
    <h2>📂 Project Structure</h2>
    <pre><code>Depression-Detection-From-Twitter-Data-Using-BERT-and-LIME-An-Explainable-AI-Approach/
├── Code/Code.ipynb
├── Dataset/Training dataset/Training.csv
├── Dataset/Testing dataset/user_tweets.csv
├── requirements.txt
├── images
├── README.md
</code></pre>
  </div>

  <div class="section">
    <h2>🚀 Usage</h2>
    <ol>
      <li>Clone the repo:<br>
        <pre><code>https://github.com/Vikash-hp/Depression-Detection-From-Twitter-Data-Using-BERT-and-LIME-An-Explainable-AI-Approach.git</code></pre>
      </li>
      <li>Install dependencies:<br>
        <pre><code>pip install -r requirements.txt</code></pre>
      </li>
      <li>Add <code>Training.csv</code> and <code>user_tweets.csv</code> to the project root.</li>
      <li>Run <code>Code.ipynb</code> in Jupyter Notebook or JupyterLab.</li>
    </ol>
  </div>

  <div class="section">
    <h2>🔍 Code Overview</h2>
    <ul>
      <li>Library Setup</li>
      <li>Dataset Preprocessing</li>
      <li>BERT Model Training</li>
      <li>LIME Integration for Explanations</li>
      <li>Model Evaluation and Visualization</li>
    </ul>
  </div>

  <div class="section">
    <h2>📊 Example Outputs</h2>
    <ul>
      <li><strong>Classification Report:</strong> Precision, Recall, F1-score</li>
      <li><strong>Confusion Matrix:</strong> Visual of prediction accuracy</li>
      <li><strong>LIME Explanations:</strong> Graphically represent tweets that contribute to the model's predictions.</li>
    </ul>
  </div>

  <div class="section">
    <h2>📸 Output Screenshots</h2>
    <ul>
      <li><strong>Confusion Matrix:</strong></li>
      <img src="images/confusion matrix.png" alt="confusion matrix loading..." style="max-width:100%; border:1px solid #ccc; border-radius:8px; margin-top:10px;">
      <li><strong>Classification and LIME Explanation:</strong></li>
      <img src="images/classification and lime explanation.png" alt="LIME Explanation loading..." style="max-width:100%; border:1px solid #ccc; border-radius:8px; margin-top:10px;">
    </ul>
  </div>

  <div class="section">
    <h2>⚠️ Limitations</h2>
    <ul>
      <li>Performance depends on dataset quality and size</li>
      <li>LIME explanations are local, not global</li>
      <li>GPU recommended for faster training</li>
    </ul>
  </div>

  <div class="section">
    <h2>🔮 Future Improvements</h2>
    <ul>
      <li>Better preprocessing (emoji/URL removal)</li>
      <li>Try other transformer models like RoBERTa</li>
      <li>Enhance LIME visualizations</li>
      <li>Deploy as a web app</li>
    </ul>
  </div>

  <div class="section">
    <h2>👨‍🏫 Supervised By</h2>
    <ul>
      <li>Dr. Jyoti Prakash Singh, Associate Professor, CSE, NIT Patna</li>
    </ul>
    <h2>👨‍💻 Contributed By</h2>
    <ul>
      <li>Shivani Saroj, CSE, NIT Patna</li>
      <li>Gyan Ranjan Nayak, CSE, NIT Patna</li>
    </ul>
  </div>

  <div class="section">
    <h2>🤝 For More Contribution</h2>
    <ol>
      <li>Fork the repo</li>
      <li>Create a feature branch: <code>git checkout -b feature/your-feature</code></li>
      <li>Commit your changes: <code>git commit -m 'Add your feature'</code></li>
      <li>Push: <code>git push origin feature/your-feature</code></li>
      <li>Open a Pull Request</li>
    </ol>
  </div>

  <div class="section">
    <h2>📬 Contact</h2>
    <p>For questions, open an issue or contact <a href="mailto:vikash2206133@gmail.com">vikash2206133@gmail.com</a>.</p>
  </div>

  <hr/>
  <p><em>Built with ❤️ for explainable AI research.</em></p>

</body>
</html>
