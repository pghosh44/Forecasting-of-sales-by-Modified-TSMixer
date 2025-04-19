<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

  <h1>SentiTSMixer - Running the Colab Notebook</h1>

  <p>This README will guide you through the process of setting up and running the notebook.<br>
  You need <strong>Python 3.9.20</strong> to be installed beforehand.</p>

  <hr>

  <h2>Prerequisites</h2>
  <p>Before running the Colab notebooks, ensure you have the necessary dependencies installed.
  You can install the required packages by running the <code>requirements.txt</code> file.</p>

  <hr>

  <h2>Step-by-step Instructions</h2>

  <h3>1. Install Dependencies from <code>requirements.txt</code></h3>
  <p>Install the required packages using:</p>
  <pre><code>pip install -r requirements.txt</code></pre>

  <hr>

  <h3>2. Open the Colab Notebooks</h3>
  <p>There are <strong>two Jupyter notebooks</strong> included in this project:</p>
  <ul>
    <li><strong>Magazine_BERT_SentimentAnalysis</strong></li>
    <li><strong>Magazine_VADER_SentimentAnalysis</strong></li>
  </ul>

  <p>To run them in Google Colab:</p>
  <ol>
    <li>Open the notebook (either BERT or VADER) in Colab using its URL or by uploading it directly.</li>
    <li>Click the <strong>“Connect”</strong> button in the top-right to connect to a runtime.</li>
  </ol>

  <p><strong>Note:</strong> The <em>dataset path needs to be updated</em> in the notebook based on your file location before running.</p>

  <hr>

  <h3>3. Running the Colab Code</h3>
  <p>The notebooks are divided into cells. Run each cell in order:</p>
  <ul>
    <li>Click the <strong>Play</strong> button beside each cell</li>
    <li>Or press <strong>Shift + Enter</strong> to execute</li>
  </ul>

  <p><strong>Tip:</strong> Run cells sequentially to avoid errors.</p>

  <hr>

  <h3>4. Key Steps in the Notebooks</h3>
  <ul>
    <li><strong>Install Dependencies:</strong> The first cell usually installs required packages using pip.</li>
    <li><strong>Set up Environment:</strong> Configure variables, download resources, and prepare data.</li>
    <li><strong>Update Dataset Path:</strong> Ensure dataset path is correct before loading data.</li>
    <li><strong>Run Sentiment Analysis:</strong> Execute code blocks that perform sentiment analysis using BERT or VADER.</li>
    <li><strong>Review Output:</strong> Check final results, predictions, or visualizations.</li>
  </ul>

  <hr>

  <h3>5. Troubleshooting</h3>
  <ul>
    <li>Make sure all dependencies are installed.</li>
    <li>Verify the dataset path is accurate.</li>
    <li>Run cells in correct order to maintain state.</li>
    <li>Ensure internet access and file permissions are in place.</li>
  </ul>

  <p>Feel free to reach out to us if you have any questions or face difficulties.</p>

</body>
</html>
